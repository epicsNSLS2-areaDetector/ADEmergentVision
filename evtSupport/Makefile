TOP=..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

SRC_DIRS = ../include

INC += cemergentexception.h
INC += EmergentAVIFile.h
INC += EmergentCameraAPIs.h
INC += EmergentCameraC.h
INC += emergentcameradef.h
INC += EmergentCamera.h
INC += emergenterrors.h
INC += emergentframebase.h
INC += emergentframeconvertbitdepth.h
INC += emergentframeconvertcolor.h
INC += emergentframeconverterbase.h
INC += emergentframe.h
INC += EmergentFrameSave.h
INC += emergentframeunpack.h
INC += EmergentGenICamNodeCallback.h
INC += EmergentGenICamNodeT.h
INC += emergentgigevisiondef.h
INC += EvtParamAttribute.h
INC += GenTL.h
INC += gigevisiondeviceinfo.h
INC += networkinterfacecontroller.h
INC += platformsymbols.h


# Note, the following files were manually copied from the EmergentVision /eSDK/lib directory
# to this directory after building


ifeq (linux-x86_64, $(findstring linux-x86_64, $(T_A)))
LIB_INSTALLS_Linux += ../os/$(EPICS_HOST_ARCH)/libEmergentCameraC.so
LIB_INSTALLS_Linux += ../os/$(EPICS_HOST_ARCH)/libEmergentCamera.so
LIB_INSTALLS_Linux += ../os/$(EPICS_HOST_ARCH)/libEmergentGenICam.so
LIB_INSTALLS_Linux += ../os/$(EPICS_HOST_ARCH)/libEmergentGigEVision.so
LIB_INSTALLS_Linux += ../os/$(EPICS_HOST_ARCH)/libvma.so
endif

#=============================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

# Note, the following files were manually copied from the Prosilica GigESDK/bin-pc directory
# to this directory after building



