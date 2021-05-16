
################################################################################
# Automatically-generated file. Do not edit!
################################################################################

ifdef SystemRoot
	SHELL = cmd.exe
	MK_DIR = mkdir
else
	ifeq ($(shell uname), Linux)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), CYGWIN)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW32)
		MK_DIR = mkdir -p
	endif

	ifeq ($(shell uname | cut -d _ -f 1), MINGW64)
		MK_DIR = mkdir -p
	endif
endif

# List the subdirectories for creating object files
SUB_DIRS +=  \
 \
hpl/adc \
hal/src \
examples \
hpl/systick \
hpl/oscctrl \
saml21b/armcc/Device/SAML21B/Source \
hpl/tc \
hpl/osc32kctrl \
usb \
hpl/dmac \
usb/class/cdc/device \
hal/utils/src \
hpl/rtc \
usb/class/hid/device \
hpl/usb \
hpl/mclk \
hpl/gclk \
usb/device \
hpl/pm \
hpl/dac \
saml21b/armcc/Device/SAML21B/Source/ARM \
hpl/sercom \
hpl/nvmctrl \
hpl/core \
usb/class/msc/device

# List the object files
OBJS +=  \
hal/src/hal_io.o \
saml21b/armcc/Device/SAML21B/Source/system_saml21.o \
hpl/systick/hpl_systick.o \
hal/src/hal_calendar.o \
saml21b/armcc/Device/SAML21B/Source/ARM/startup_SAML21.o \
usb/class/hid/device/hiddf_generic.o \
usb/class/cdc/device/cdcdf_acm.o \
hpl/mclk/hpl_mclk.o \
hpl/nvmctrl/hpl_nvmctrl.o \
usb/class/msc/device/mscdf.o \
hal/src/hal_spi_m_sync.o \
hal/src/hal_timer.o \
hal/src/hal_pwm.o \
hpl/usb/hpl_usb.o \
hal/src/hal_i2c_m_sync.o \
hal/src/hal_delay.o \
hpl/pm/hpl_pm.o \
hpl/core/hpl_init.o \
hal/utils/src/utils_list.o \
hpl/core/hpl_core_m0plus_base.o \
hal/utils/src/utils_assert.o \
hpl/dmac/hpl_dmac.o \
hpl/oscctrl/hpl_oscctrl.o \
usb/class/hid/device/hiddf_keyboard.o \
usb/usb_protocol.o \
hpl/dac/hpl_dac.o \
hpl/gclk/hpl_gclk.o \
hal/src/hal_flash.o \
hal/src/hal_init.o \
hal/src/hal_usb_device.o \
main.o \
hpl/osc32kctrl/hpl_osc32kctrl.o \
hpl/rtc/hpl_rtc.o \
examples/driver_examples.o \
driver_init.o \
hal/src/hal_usart_async.o \
hal/src/hal_adc_sync.o \
hal/src/hal_dac_sync.o \
hpl/sercom/hpl_sercom.o \
hal/utils/src/utils_ringbuffer.o \
hal/src/hal_gpio.o \
usb/class/hid/device/hiddf_mouse.o \
hal/utils/src/utils_event.o \
hal/src/hal_sleep.o \
usb_start.o \
atmel_start.o \
usb/device/usbdc.o \
hpl/tc/hpl_tc.o \
hal/src/hal_atomic.o \
hpl/adc/hpl_adc.o

OBJS_AS_ARGS +=  \
"hal/src/hal_io.o" \
"saml21b/armcc/Device/SAML21B/Source/system_saml21.o" \
"hpl/systick/hpl_systick.o" \
"hal/src/hal_calendar.o" \
"saml21b/armcc/Device/SAML21B/Source/ARM/startup_SAML21.o" \
"usb/class/hid/device/hiddf_generic.o" \
"usb/class/cdc/device/cdcdf_acm.o" \
"hpl/mclk/hpl_mclk.o" \
"hpl/nvmctrl/hpl_nvmctrl.o" \
"usb/class/msc/device/mscdf.o" \
"hal/src/hal_spi_m_sync.o" \
"hal/src/hal_timer.o" \
"hal/src/hal_pwm.o" \
"hpl/usb/hpl_usb.o" \
"hal/src/hal_i2c_m_sync.o" \
"hal/src/hal_delay.o" \
"hpl/pm/hpl_pm.o" \
"hpl/core/hpl_init.o" \
"hal/utils/src/utils_list.o" \
"hpl/core/hpl_core_m0plus_base.o" \
"hal/utils/src/utils_assert.o" \
"hpl/dmac/hpl_dmac.o" \
"hpl/oscctrl/hpl_oscctrl.o" \
"usb/class/hid/device/hiddf_keyboard.o" \
"usb/usb_protocol.o" \
"hpl/dac/hpl_dac.o" \
"hpl/gclk/hpl_gclk.o" \
"hal/src/hal_flash.o" \
"hal/src/hal_init.o" \
"hal/src/hal_usb_device.o" \
"main.o" \
"hpl/osc32kctrl/hpl_osc32kctrl.o" \
"hpl/rtc/hpl_rtc.o" \
"examples/driver_examples.o" \
"driver_init.o" \
"hal/src/hal_usart_async.o" \
"hal/src/hal_adc_sync.o" \
"hal/src/hal_dac_sync.o" \
"hpl/sercom/hpl_sercom.o" \
"hal/utils/src/utils_ringbuffer.o" \
"hal/src/hal_gpio.o" \
"usb/class/hid/device/hiddf_mouse.o" \
"hal/utils/src/utils_event.o" \
"hal/src/hal_sleep.o" \
"usb_start.o" \
"atmel_start.o" \
"usb/device/usbdc.o" \
"hpl/tc/hpl_tc.o" \
"hal/src/hal_atomic.o" \
"hpl/adc/hpl_adc.o"

# List the dependency files
DEPS := $(OBJS:%.o=%.d)

DEPS_AS_ARGS +=  \
"usb/usb_protocol.d" \
"hal/src/hal_calendar.d" \
"hal/utils/src/utils_event.d" \
"hal/src/hal_io.d" \
"hpl/systick/hpl_systick.d" \
"usb/class/hid/device/hiddf_generic.d" \
"usb/class/cdc/device/cdcdf_acm.d" \
"usb/class/hid/device/hiddf_mouse.d" \
"hal/src/hal_i2c_m_sync.d" \
"hpl/usb/hpl_usb.d" \
"usb/class/msc/device/mscdf.d" \
"hpl/nvmctrl/hpl_nvmctrl.d" \
"hal/src/hal_pwm.d" \
"hal/src/hal_timer.d" \
"hal/src/hal_spi_m_sync.d" \
"hpl/core/hpl_core_m0plus_base.d" \
"hal/utils/src/utils_list.d" \
"hpl/dmac/hpl_dmac.d" \
"hal/utils/src/utils_assert.d" \
"hpl/mclk/hpl_mclk.d" \
"hal/src/hal_delay.d" \
"hpl/core/hpl_init.d" \
"hpl/pm/hpl_pm.d" \
"hal/src/hal_flash.d" \
"hpl/gclk/hpl_gclk.d" \
"saml21b/armcc/Device/SAML21B/Source/system_saml21.d" \
"hal/src/hal_usb_device.d" \
"usb_start.d" \
"hal/src/hal_init.d" \
"usb/class/hid/device/hiddf_keyboard.d" \
"hpl/dac/hpl_dac.d" \
"driver_init.d" \
"hal/src/hal_adc_sync.d" \
"hal/src/hal_usart_async.d" \
"hpl/osc32kctrl/hpl_osc32kctrl.d" \
"main.d" \
"examples/driver_examples.d" \
"hpl/rtc/hpl_rtc.d" \
"hal/src/hal_sleep.d" \
"hal/utils/src/utils_ringbuffer.d" \
"hpl/sercom/hpl_sercom.d" \
"hal/src/hal_dac_sync.d" \
"hal/src/hal_gpio.d" \
"saml21b/armcc/Device/SAML21B/Source/ARM/startup_SAML21.d" \
"hal/src/hal_atomic.d" \
"hpl/tc/hpl_tc.d" \
"usb/device/usbdc.d" \
"hpl/oscctrl/hpl_oscctrl.d" \
"hpl/adc/hpl_adc.d" \
"atmel_start.d"

OUTPUT_FILE_NAME :=AtmelStart
QUOTE := "
OUTPUT_FILE_PATH +=$(OUTPUT_FILE_NAME).elf
OUTPUT_FILE_PATH_AS_ARGS +=$(OUTPUT_FILE_NAME).elf

vpath %.c ../
vpath %.s ../
vpath %.S ../

# All Target
all: $(SUB_DIRS) $(OUTPUT_FILE_PATH)

# Linker target

$(OUTPUT_FILE_PATH): $(OBJS)
	@echo Building target: $@
	@echo Invoking: ARMCC Linker
	$(QUOTE)armlink$(QUOTE) --ro-base 0x00000000 --entry 0x00000000 --rw-base 0x20000000 --entry Reset_Handler --first __Vectors \
--strict --summary_stderr --info summarysizes --map --xref --callgraph --symbols \
--info sizes --info totals --info unused --info veneers --list $(OUTPUT_FILE_NAME).map \
-o $(OUTPUT_FILE_NAME).elf --cpu Cortex-M0+ \
$(OBJS_AS_ARGS)

	@echo Finished building target: $@

# Compiler target(s)




%.o: %.c
	@echo Building file: $<
	@echo ARMCC Compiler
	$(QUOTE)armcc$(QUOTE) --c99 -c -DDEBUG -O1 -g --apcs=interwork --split_sections --cpu Cortex-M0+ -D__SAML21G18B__ \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dac" -I"../hpl/dmac" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/usb" -I"../hri" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/composite/device" -I"../usb/class/hid" -I"../usb/class/hid/device" -I"../usb/class/hub" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/class/vendor" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../saml21b/include"  \
--depend "$@"  -o "$@" "$<"

	@echo Finished building: $<

%.o: %.s
	@echo Building file: $<
	@echo ARMCC Assembler
	$(QUOTE)armasm$(QUOTE) -g --apcs=interwork --cpu Cortex-M0+ --pd "D__SAML21G18B__ SETA 1" \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dac" -I"../hpl/dmac" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/usb" -I"../hri" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/composite/device" -I"../usb/class/hid" -I"../usb/class/hid/device" -I"../usb/class/hub" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/class/vendor" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../saml21b/include"  \
--depend "$(@:%.o=%.d)" -o "$@" "$<"

	@echo Finished building: $<

%.o: %.S
	@echo Building file: $<
	@echo ARMCC Preprocessing Assembler
	$(QUOTE)armcc$(QUOTE) --c99 -c -DDEBUG -O1 -g --apcs=interwork --split_sections --cpu Cortex-M0+ -D__SAML21G18B__ \
-I"../" -I"../config" -I"../examples" -I"../hal/include" -I"../hal/utils/include" -I"../hpl/adc" -I"../hpl/core" -I"../hpl/dac" -I"../hpl/dmac" -I"../hpl/gclk" -I"../hpl/mclk" -I"../hpl/nvmctrl" -I"../hpl/osc32kctrl" -I"../hpl/oscctrl" -I"../hpl/pm" -I"../hpl/port" -I"../hpl/rtc" -I"../hpl/sercom" -I"../hpl/systick" -I"../hpl/tc" -I"../hpl/usb" -I"../hri" -I"../" -I"../config" -I"../usb" -I"../usb/class/cdc" -I"../usb/class/cdc/device" -I"../usb/class/composite/device" -I"../usb/class/hid" -I"../usb/class/hid/device" -I"../usb/class/hub" -I"../usb/class/msc" -I"../usb/class/msc/device" -I"../usb/class/vendor" -I"../usb/device" -I"../" -I"../CMSIS/Core/Include" -I"../saml21b/include"  \
--depend "$@"  -o "$@" "$<"

	@echo Finished building: $<

# Detect changes in the dependent files and recompile the respective object files.
ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(DEPS)),)
-include $(DEPS)
endif
endif

$(SUB_DIRS):
	$(MK_DIR) "$@"

clean:
	rm -f $(OBJS_AS_ARGS)
	rm -f $(OUTPUT_FILE_PATH)
	rm -f $(DEPS_AS_ARGS)
	rm -f $(OUTPUT_FILE_NAME).map $(OUTPUT_FILE_NAME).elf
