# User Test
#------------------------------------
APP              = test
# App sources
APP_SRCS         = helloworld.c
# App includes
APP_INC	         = $(PWD)/test
# Compiler flags
APP_CFLAGS       =
# Linker flags
APP_LDFLAGS      =

# Custom linker
APP_LINK_SCRIPT  =

INCLUDES += -I$(PWD)/test

APP_CFLAGS += $(INCLUDES)

include $(RULES_DIR)/pmsis_rules.mk
