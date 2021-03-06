#
# Makefile for the touchscreen drivers.
#

# Each configuration option enables a list of files.

wm97xx-ts-y := wm97xx-core.o
obj-y                  			+= ct36x/
obj-$(CONFIG_TOUCHSCREEN_88PM860X)	+= 88pm860x-ts.o
obj-$(CONFIG_TOUCHSCREEN_AD7877)	+= ad7877.o
obj-$(CONFIG_TOUCHSCREEN_AD7879)	+= ad7879.o
obj-$(CONFIG_TOUCHSCREEN_AD7879_I2C)	+= ad7879-i2c.o
obj-$(CONFIG_TOUCHSCREEN_AD7879_SPI)	+= ad7879-spi.o
obj-$(CONFIG_TOUCHSCREEN_ADS7846)	+= ads7846.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_MXT)	+= atmel_mxt_ts.o
obj-$(CONFIG_TOUCHSCREEN_ATMEL_TSADCC)	+= atmel_tsadcc.o
obj-$(CONFIG_TOUCHSCREEN_BITSY)		+= h3600_ts_input.o
obj-$(CONFIG_TOUCHSCREEN_BU21013)       += bu21013_ts.o
obj-$(CONFIG_TOUCHSCREEN_CY8CTMG110)	+= cy8ctmg110_ts.o
obj-$(CONFIG_TOUCHSCREEN_DA9034)	+= da9034-ts.o
obj-$(CONFIG_TOUCHSCREEN_DYNAPRO)	+= dynapro.o
obj-$(CONFIG_TOUCHSCREEN_HAMPSHIRE)	+= hampshire.o
obj-$(CONFIG_TOUCHSCREEN_GUNZE)		+= gunze.o
obj-$(CONFIG_TOUCHSCREEN_EETI)		+= eeti_ts.o
obj-$(CONFIG_TOUCHSCREEN_ELO)		+= elo.o
obj-$(CONFIG_TOUCHSCREEN_FUJITSU)	+= fujitsu_ts.o
obj-$(CONFIG_TOUCHSCREEN_INEXIO)	+= inexio.o
obj-$(CONFIG_TOUCHSCREEN_INTEL_MID)	+= intel-mid-touch.o
obj-$(CONFIG_TOUCHSCREEN_LPC32XX)	+= lpc32xx_ts.o
obj-$(CONFIG_TOUCHSCREEN_MAX11801)	+= max11801_ts.o
obj-$(CONFIG_TOUCHSCREEN_MC13783)	+= mc13783_ts.o
obj-$(CONFIG_TOUCHSCREEN_MCS5000)	+= mcs5000_ts.o
obj-$(CONFIG_TOUCHSCREEN_MIGOR)		+= migor_ts.o
obj-$(CONFIG_TOUCHSCREEN_MTOUCH)	+= mtouch.o
obj-$(CONFIG_TOUCHSCREEN_MK712)		+= mk712.o
obj-$(CONFIG_TOUCHSCREEN_HP600)		+= hp680_ts_input.o
obj-$(CONFIG_TOUCHSCREEN_HP7XX)		+= jornada720_ts.o
obj-$(CONFIG_TOUCHSCREEN_HTCPEN)	+= htcpen.o
obj-$(CONFIG_TOUCHSCREEN_USB_COMPOSITE)	+= usbtouchscreen.o
obj-$(CONFIG_TOUCHSCREEN_PCAP)		+= pcap_ts.o
obj-$(CONFIG_TOUCHSCREEN_PENMOUNT)	+= penmount.o
obj-$(CONFIG_TOUCHSCREEN_S3C2410)	+= s3c2410_ts.o
obj-$(CONFIG_TOUCHSCREEN_ST1232)	+= st1232.o
obj-$(CONFIG_TOUCHSCREEN_STMPE)		+= stmpe-ts.o
obj-$(CONFIG_TOUCHSCREEN_TNETV107X)	+= tnetv107x-ts.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_I2C_RMI)	+= synaptics_i2c_rmi.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHIT213)	+= touchit213.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHRIGHT)	+= touchright.o
obj-$(CONFIG_TOUCHSCREEN_TOUCHWIN)	+= touchwin.o
obj-$(CONFIG_TOUCHSCREEN_TSC2005)	+= tsc2005.o
obj-$(CONFIG_TOUCHSCREEN_TSC2007)	+= tsc2007.o
obj-$(CONFIG_TOUCHSCREEN_UCB1400)	+= ucb1400_ts.o
obj-$(CONFIG_TOUCHSCREEN_WACOM_W8001)	+= wacom_w8001.o
obj-$(CONFIG_TOUCHSCREEN_WM831X)	+= wm831x-ts.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX)	+= wm97xx-ts.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9705)	+= wm9705.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9712)	+= wm9712.o
wm97xx-ts-$(CONFIG_TOUCHSCREEN_WM9713)	+= wm9713.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_ATMEL)	+= atmel-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_MAINSTONE)	+= mainstone-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_WM97XX_ZYLONITE)	+= zylonite-wm97xx.o
obj-$(CONFIG_TOUCHSCREEN_W90X900)	+= w90p910_ts.o
obj-$(CONFIG_TOUCHSCREEN_TPS6507X)	+= tps6507x-ts.o
obj-$(CONFIG_TOUCHSCREEN_PCAP)		+= pcap_ts.o
obj-$(CONFIG_TOUCHSCREEN_XPT2046_NORMAL_SPI)	+= xpt2046_ts.o
obj-$(CONFIG_TOUCHSCREEN_XPT2046_TSLIB_SPI)	+= xpt2046_tslib_ts.o ts_lib/
obj-$(CONFIG_TOUCHSCREEN_XPT2046_CBN_SPI)	+= xpt2046_cbn_ts.o calibration_ts.o largenum_ts.o calib_iface_ts.o
obj-$(CONFIG_TOUCHSCREEN_IT7250)	+= ctp_it7250.o
obj-$(CONFIG_RK28_I2C_TS_NTP070)	+= ntp070.o
obj-$(CONFIG_HANNSTAR_P1003)		+= hannstar_p1003.o
obj-$(CONFIG_TOUCHSCREEN_IT7260)	+= it7260_ts.o
obj-$(CONFIG_TOUCHSCREEN_IT7260_I2C)	+= IT7260_ts_i2c.o
obj-$(CONFIG_SINTEK_3FA16)		+= sintek_3FA16.o
obj-$(CONFIG_EETI_EGALAX)		+= eeti_egalax_i2c.o
obj-$(CONFIG_ATMEL_MXT224)		+= atmel_maxtouch.o
obj-$(CONFIG_ATMEL_MXT1386)		+= atmel_mxt1386.o
obj-$(CONFIG_TOUCHSCREEN_GT801_IIC)	+= gt801_ts.o
obj-$(CONFIG_TOUCHSCREEN_GT811_IIC)	+= gt811_ts.o
obj-$(CONFIG_TOUCHSCREEN_86V_GT811_IIC)	+= 86v_gt811_ts.o
obj-$(CONFIG_TOUCHSCREEN_GT82X_IIC)	+= goodix_touch_82x.o
obj-$(CONFIG_TOUCHSCREEN_GT818_IIC)	+= gt818_ts.o
obj-$(CONFIG_TOUCHSCREEN_GT8110)        += gt8110_ts.o
obj-$(CONFIG_TOUCHSCREEN_CT360_IIC)	+= ct360_ts.o
obj-$(CONFIG_TOUCHSCREEN_ILI2102_IIC)	+= ili2102_ts.o
obj-$(CONFIG_D70_L3188A)		+= goodix_touch.o
obj-$(CONFIG_TOUCHSCREEN_GT8XX)                += rk29_i2c_goodix.o
obj-$(CONFIG_TOUCHSCREEN_FT5406)	+= ft5406_ts.o
obj-$(CONFIG_TOUCHSCREEN_FT5306)	+= ft5306_ts.o
obj-$(CONFIG_TOUCHSCREEN_SITRONIX_A720)	+= sitronix_ts_a720.o
obj-$(CONFIG_TOUCHSCREEN_FT5306_WPX2)        += ft5306_ts_wpx2.o
obj-$(CONFIG_TOUCHSCREEN_FT5306_AV) += ft5306_ts_av.o
obj-$(CONFIG_TOUCHSCREEN_GT819)		+= gt819.o
obj-$(CONFIG_TOUCHSCREEN_CT36X)		+= ct36x_ts.o
obj-$(CONFIG_TOUCHSCREEN_NAS)		+= nas_ts.o
obj-$(CONFIG_LAIBAO_TS)		+= ft5x0x_i2c_ts.o
obj-$(CONFIG_TOUCHSCREEN_PIXCIR)      += pixcir_i2c_ts.o
obj-$(CONFIG_TOUCHSCREEN_SYNAPTICS_RMI4_I2C_RK)      += rmi4/
obj-$(CONFIG_TOUCHSCREEN_I30)	+= i30_ts.o
obj-$(CONFIG_TOUCHSCREEN_BYD693X)	+= byd693x_ts.o
obj-$(CONFIG_TOUCHSCREEN_FT5X0X)	+= ft5x0x.o
obj-$(CONFIG_TOUCHSCREEN_GSLX680)	+= rockchip_gslX680.o
obj-$(CONFIG_TOUCHSCREEN_GSLX680_RK3168)	+= rockchip_gslX680_rk3168.o
obj-$(CONFIG_TOUCHSCREEN_GSLX680_RK3028)	+= rockchip_gslX680_rk3028.o
# Make VTL TouchScreen Driver
#obj-$(CONFIG_TOUCHSCREEN_CT36X)		+= ct36x_ts/
obj-$(CONFIG_TP_760_TS)                    += tp_760_ts.o
obj-y += zet62xx/
obj-y += aw5x0x/
obj-$(CONFIG_TOUCHSCREEN_AR1020_I2C)	+= ar1020-i2c.o
obj-$(CONFIG_TOUCHSCREEN_AR1020_SPI)	+= ar1020-spi.o
