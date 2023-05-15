# name of your application
APPLICATION = WINDFORME

# If no BOARD is found in the environment, use this default:
BOARD ?= nucleo-f401re

# This has to be the absolute path to the RIOT base directory:
RIOTBASE ?= $(CURDIR)/../../RIOT

# Comment this out to disable code in RIOT that does safety checking
# which is not needed in a production environment but helps in the
# development process:
DEVELHELP ?= 1

# Change this to 0 show compiler invocation lines by default:
QUIET ?= 0

# Modules to include:
USEMODULE += dht
USEMODULE += fmt
USEMODULE += xtimer
USEMODULE += periph_gpio

include $(RIOTBASE)/Makefile.include