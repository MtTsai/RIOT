APPLICATION = condition_variable
include ../Makefile.tests_common

BOARD_BLACKLIST := arduino-mega2560
# arduino-mega2560: unknown type name: clockid_t

BOARD_INSUFFICIENT_RAM := stm32f0discovery

USEMODULE += posix
USEMODULE += pthread
USEMODULE += vtimer

CFLAGS += -DNATIVE_AUTO_EXIT

include $(RIOTBASE)/Makefile.include
