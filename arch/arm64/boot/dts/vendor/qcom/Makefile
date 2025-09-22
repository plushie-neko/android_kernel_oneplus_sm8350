ifneq ($(CONFIG_ARCH_QTI_VM), y)
ifneq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAHAINA) += lahaina-rumi-overlay.dtbo \
	lahaina-mtp-overlay.dtbo \
	lahaina-mtp-hsp-overlay.dtbo \
	lahaina-cdp-overlay.dtbo \
	lahaina-qrd-overlay.dtbo \
	lahaina-atp-overlay.dtbo \
	lahaina-hdk-overlay.dtbo \
	lahaina-hhg-overlay.dtbo \
	lahainap-hhg-hsp-pro-overlay.dtbo \
	lahaina-qrd-hsp-overlay.dtbo \
	lahaina-qrd-module-overlay.dtbo \
	lahainap-mtp-overlay.dtbo \
	lahainap-cdp-overlay.dtbo \
	lahainap-atp-overlay.dtbo \
	lahainap-qrd-overlay.dtbo \
	lahaina-cdp-v2.2-overlay.dtbo \
	lahaina-mtp-v2-overlay.dtbo \
	lahaina-mtp-v2.1-overlay.dtbo \
	lahaina-mtp-hsp-pro-overlay.dtbo \
	lahaina-cdp-hsp-pro-overlay.dtbo \
	lahaina-qrd-hsp-pro-overlay.dtbo

lahaina-rumi-overlay.dtbo-base := lahaina.dtb
lahaina-mtp-hsp-overlay.dtbo-base := lahaina.dtb
lahaina-mtp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-cdp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-atp-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-hdk-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-hhg-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahainap-hhg-hsp-pro-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahaina-qrd-hsp-overlay.dtbo-base := lahaina.dtb
lahaina-qrd-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahaina-qrd-module-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb lahaina-v2.1.dtb
lahainap-mtp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-cdp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-atp-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahainap-qrd-overlay.dtbo-base := lahainap.dtb lahainap-v2.dtb lahainap-v2.1.dtb
lahaina-cdp-v2.2-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-mtp-v2-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-mtp-v2.1-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-mtp-hsp-pro-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-cdp-hsp-pro-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
lahaina-qrd-hsp-pro-overlay.dtbo-base := lahaina.dtb lahaina-v2.dtb \
					lahaina-v2.1.dtb
else
dtb-$(CONFIG_ARCH_LAHAINA) += lahaina-rumi.dtb \
	lahaina-mtp-hsp.dtb \
	lahaina-mtp.dtb \
	lahaina-cdp.dtb \
	lahaina-atp.dtb \
	lahaina-hdk.dtb \
	lahaina-qrd-hsp.dtb \
	lahaina-qrd.dtb \
	lahaina-qrd-module.dtb \
	lahainap-mtp.dtb \
	lahainap-cdp.dtb \
	lahainap-atp.dtb \
	lahainap-qrd.dtb \
	lahaina-v2-mtp.dtb \
	lahaina-v2-cdp.dtb \
	lahaina-v2-atp.dtb \
	lahaina-v2-hdk.dtb \
	lahaina-v2-qrd.dtb \
	lahaina-v2-qrd-module.dtb \
	lahainap-v2-mtp.dtb \
	lahainap-v2-cdp.dtb \
	lahainap-v2-atp.dtb \
	lahainap-v2-qrd.dtb \
	lahaina-cdp-v2.2.dtb \
	lahaina-v2.1-mtp.dtb \
	lahaina-v2.1-cdp.dtb \
	lahaina-v2.1-atp.dtb \
	lahaina-v2.1-hdk.dtb \
	lahaina-v2.1-hhg.dtb \
	lahainap-v2.1-hhg-hsp-pro.dtb \
	lahaina-v2.1-qrd.dtb \
	lahaina-v2.1-qrd-module.dtb \
	lahainap-v2.1-mtp.dtb \
	lahainap-v2.1-cdp.dtb \
	lahainap-v2.1-atp.dtb \
	lahainap-v2.1-qrd.dtb \
	lahaina-mtp-v2.dtb \
	lahaina-mtp-v2.1.dtb \
	lahaina-v2.1-mtp-hsp-pro.dts \
	lahaina-v2.1-cdp-hsp-pro.dts \
	lahaina-v2.1-qrd-hsp-pro.dts
endif
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KONA) += \
                kona-cdp-overlay.dtbo \
                kona-cdp-lcd-overlay.dtbo \
                kona-cdp-lcd-tron-overlay.dtbo \
                kona-mtp-overlay.dtbo \
                kona-mtp-ws-overlay.dtbo \
		kona-sa-mtp-overlay.dtbo \
                kona-xr-overlay.dtbo \
                kona-rumi-overlay.dtbo \
                kona-qrd-overlay.dtbo \
                kona-xrfusion-overlay.dtbo \
                kona-xrfusion-ult-overlay.dtbo \
                kona-arglass-overlay.dtbo \
                kona-xrsku4-overlay.dtbo \
                kona-hdk-overlay.dtbo

kona-cdp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-cdp-lcd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-cdp-lcd-tron-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-mtp-ws-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-sa-mtp-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xr-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-rumi-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-qrd-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrfusion-ult-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-arglass-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-xrsku4-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
kona-hdk-overlay.dtbo-base := kona.dtb kona-v2.dtb kona-v2.1.dtb
else
dtb-$(CONFIG_ARCH_KONA) += kona-rumi.dtb \
        kona-mtp.dtb \
        kona-mtp-ws.dtb \
        kona-mtp-sa.dtb \
        kona-xr.dtb \
        kona-xrfusion.dtb \
        kona-xrfusion-ult.dtb \
        kona-arglass.dtb \
        kona-xrsku4.dtb \
        kona-cdp.dtb \
        kona-cdp-lcd.dtb \
        kona-cdp-lcd-tron.dtb \
        kona-qrd.dtb \
        kona-v2-rumi.dtb \
        kona-v2-mtp.dtb \
        kona-v2-mtp-ws.dtb \
        kona-v2-mtp-sa.dtb \
        kona-v2-cdp.dtb \
        kona-v2-qrd.dtb \
        kona-v2-xrfusion.dtb \
        kona-v2-xrfusion-ult.dtb \
        kona-v2-arglass.dtb \
        kona-v2-xrsku4.dtb \
        kona-hdk.dtb \
        kona-v2.1-mtp.dtb \
        kona-v2.1-mtp-ws.dtb \
        kona-v2.1-mtp-sa.dtb \
        kona-v2.1-cdp.dtb \
        kona-v2.1-qrd.dtb \
        kona-v2.1-hdk.dtb \
        kona-v2.1-xrfusion.dtb \
        kona-v2.1-xrfusion-ult.dtb \
        kona-v2.1-arglass.dtb \
        kona-v2.1-xrsku4.dtb \
        qrb5165-iot-rb5.dtb \
        qrb5165m-iot-rb5.dtb \
        qrb5165n-iot-rb5.dtb \
        qrb5165n-v2-iot-rb5.dtb \
        kona-v2.1-iot-rb5.dtb \
        kona-7230-iot-rb5.dtb \
        kona-7230m-iot-rb5.dtb

endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LITO) += lito-rumi-overlay.dtbo \
                lito-mtp-overlay.dtbo \
                lito-v2-mtp-overlay.dtbo \
                lito-cdp-overlay.dtbo \
                lito-v2-cdp-overlay.dtbo \
                lito-atp-overlay.dtbo \
                lito-v2-atp-overlay.dtbo \
                lito-v2-atp-lcd-overlay.dtbo \
                lito-qrd-overlay.dtbo \
                lito-v2-qrd-overlay.dtbo \
                litomagnus-mtp-overlay.dtbo \
                litomagnus-cdp-overlay.dtbo \
                orchid-mtp-overlay.dtbo \
                orchid-cdp-overlay.dtbo

lito-rumi-overlay.dtbo-base := lito.dtb lito-v2.dtb
lito-mtp-overlay.dtbo-base := lito.dtb
lito-v2-mtp-overlay.dtbo-base := lito-v2.dtb
lito-cdp-overlay.dtbo-base := lito.dtb
lito-v2-cdp-overlay.dtbo-base := lito-v2.dtb
lito-atp-overlay.dtbo-base := lito.dtb
lito-v2-atp-overlay.dtbo-base := lito-v2.dtb
lito-v2-atp-lcd-overlay.dtbo-base := lito-v2.dtb
lito-qrd-overlay.dtbo-base := lito.dtb
lito-v2-qrd-overlay.dtbo-base := lito-v2.dtb
litomagnus-mtp-overlay.dtbo-base := litomagnus.dtb
litomagnus-cdp-overlay.dtbo-base := litomagnus.dtb
orchid-mtp-overlay.dtbo-base := orchid.dtb
orchid-cdp-overlay.dtbo-base := orchid.dtb
else
dtb-$(CONFIG_ARCH_LITO) += lito-rumi.dtb \
                lito-mtp.dtb \
                lito-cdp.dtb \
                lito-atp.dtb \
                lito-qrd.dtb \
                lito-v2-mtp.dtb \
                lito-v2-cdp.dtb \
                lito-v2-atp.dtb \
                lito-v2-atp-lcd.dtb \
                lito-v2-qrd.dtb \
                litomagnus-mtp.dtb \
                litomagnus-cdp.dtb \
                orchid-mtp.dtb \
                orchid-cdp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi-overlay.dtbo \
		lagoon-mtp-overlay.dtbo \
		lagoon-mtp-usbc-overlay.dtbo \
		lagoon-cdp-overlay.dtbo \
		lagoon-atp-overlay.dtbo \
		lagoon-qrd-overlay.dtbo

lagoon-rumi-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-overlay.dtbo-base := lagoon.dtb
lagoon-mtp-usbc-overlay.dtbo-base := lagoon.dtb
lagoon-cdp-overlay.dtbo-base := lagoon.dtb
lagoon-atp-overlay.dtbo-base := lagoon.dtb
lagoon-qrd-overlay.dtbo-base := lagoon.dtb
else
dtb-$(CONFIG_ARCH_LAGOON) += \
		lagoon-rumi.dtb \
		lagoon-mtp.dtb \
		lagoon-mtp-usbc.dtb \
		lagoon-cdp.dtb \
		lagoon-atp.dtb \
		lagoon-qrd.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_BENGAL) += \
                bengal-rumi-overlay.dtbo \
                bengal-qrd-overlay.dtbo \
                bengal-idp-overlay.dtbo \
                bengal-idp-nopmi-overlay.dtbo \
                bengal-idp-usbc-overlay.dtbo \
                bengalp-idp-overlay.dtbo \
                bengal-idp-1gb-overlay.dtbo \
                bengal-idp-2gb-overlay.dtbo \
                bengal-idp-usbc-1gb-overlay.dtbo \
                bengal-idp-usbc-2gb-overlay.dtbo \
                bengal-iot-idp-overlay.dtbo \
                bengalp-iot-idp-overlay.dtbo \
                bengal-iot-idp-2gb-overlay.dtbo \
                bengal-iot-idp-usbc-2gb-overlay.dtbo \
                bengal-iot-idp-usbc-overlay.dtbo \
                bengalp-iot-idp-2gb-overlay.dtbo \
                bengalp-iot-idp-usbc-2gb-overlay.dtbo \
                bengalp-iot-idp-usbc-overlay.dtbo

bengal-rumi-overlay.dtbo-base := bengal.dtb
bengal-qrd-overlay.dtbo-base := bengal.dtb
bengal-idp-overlay.dtbo-base := bengal.dtb
bengal-idp-nopmi-overlay.dtbo-base := bengal.dtb
bengal-idp-usbc-overlay.dtbo-base := bengal.dtb
bengalp-idp-overlay.dtbo-base := bengalp.dtb
bengal-idp-1gb-overlay.dtbo-base := bengal-1gb.dtb
bengal-idp-2gb-overlay.dtbo-base := bengal-2gb.dtb
bengal-idp-usbc-1gb-overlay.dtbo-base := bengal-1gb.dtb
bengal-idp-usbc-2gb-overlay.dtbo-base := bengal-2gb.dtb
bengal-iot-idp-overlay.dtbo-base := bengal-iot.dtb
bengalp-iot-idp-overlay.dtbo-base := bengalp-iot.dtb
bengal-iot-idp-2gb-overlay.dtbo-base := bengal-iot-2gb.dtb
bengal-iot-idp-usbc-2gb-overlay.dtbo-base := bengal-iot-2gb.dtb
bengal-iot-idp-usbc-overlay.dtbo-base := bengal-iot.dtb
bengalp-iot-idp-2gb-overlay.dtbo-base := bengalp-iot-2gb.dtb
bengalp-iot-idp-usbc-2gb-overlay.dtbo-base := bengalp-iot-2gb.dtb
bengalp-iot-idp-usbc-overlay.dtbo-base := bengalp-iot.dtb
else
dtb-$(CONFIG_ARCH_BENGAL) += bengal-rumi.dtb \
                bengal-qrd.dtb \
		bengal-idp.dtb \
		bengal-idp-nopmi.dtb \
		bengal-idp-usbc.dtb \
		bengalp-idp.dtb \
		bengal-idp-1gb.dtb \
		bengal-idp-2gb.dtb \
		bengal-idp-usbc-1gb.dtb \
		bengal-idp-usbc-2gb.dtb \
		bengal-iot-idp.dtb \
		bengalp-iot-idp.dtb \
		bengal-iot-idp-2gb.dtb \
		bengal-iot-idp-usbc-2gb.dtb \
		bengal-iot-idp-usbc.dtb \
		bengalp-iot-idp-2gb.dtb \
		bengalp-iot-idp-usbc-2gb.dtb \
		bengalp-iot-idp-usbc.dtb \
		bengalp-iot-idp-2gb.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SCUBA) += \
		scuba-rumi-overlay.dtbo \
		scuba-idp-overlay.dtbo \
		scuba-idp-usbc-overlay.dtbo \
		scuba-qrd-eldo-overlay.dtbo \
		scuba-qrd-non-eldo-overlay.dtbo \
		scuba-iot-idp-overlay.dtbo \
		scuba-iot-idp-usbc-overlay.dtbo \
		scuba-iot-qrd-eldo-overlay.dtbo \
		scuba-iot-qrd-non-eldo-overlay.dtbo \
		scuba-iot-rb1-overlay.dtbo \
		scubalite-iot-idp-overlay.dtbo

scuba-rumi-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-non-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-usbc-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-iot-idp-overlay.dtbo-base := scuba-iot.dtb scuba-iot-2gb.dtb scubap-iot.dtb scubap-iot-idp.dtb scubap-iot-idp-2gb.dtb
scuba-iot-qrd-eldo-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
scuba-iot-qrd-non-eldo-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
scuba-iot-rb1-overlay.dtbo-base := scubap-iot-2gb.dtb
scuba-iot-idp-usbc-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
scubalite-iot-idp-overlay.dtbo-base := scuba-iot-2gb.dtb scubap-iot-2gb.dtb
else
dtb-$(CONFIG_ARCH_SCUBA) += scuba-rumi.dtb \
	scuba-idp.dtb \
	scuba-idp-usbc.dtb \
	scuba-qrd-eldo.dtb \
	scuba-qrd-non-eldo.dtb \
	scubap-idp.dtb \
	scubap-idp-2gb.dtb \
	scuba-idp-2gb.dtb \
	scuba-idp-usbc-2gb.dtb \
	scuba-iot-idp.dtb \
	scuba-iot-idp-usbc.dtb \
	scubap-iot-idp.dtb \
	scuba-iot-qrd-eldo.dtb \
	scuba-iot-qrd-non-eldo.dtb \
	scubap-iot-rb1-2gb.dtb \
	scubap-iot-idp-2gb.dtb \
	scuba-iot-idp-2gb.dtb \
	scuba-iot-idp-usbc-2gb.dtb \
	scubalite-iot-idp-2gb.dtb \
	scubaplite-iot-idp-2gb.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KHAJE) += \
		khaje-atp-overlay.dtbo \
		khaje-qrd-overlay.dtbo \
		khaje-qrd-hvdcp3p5-overlay.dtbo \
		khaje-qrd-nowcd9375-overlay.dtbo \
		khaje-qrd-nopmi-overlay.dtbo \
		khaje-idp-overlay.dtbo \
		khaje-idp-nopmi-overlay.dtbo \
		khaje-idp-usbc-overlay.dtbo \
		khaje-idp-pm8010-overlay.dtbo \
		khaje-idps-display-90hz-overlay.dtbo \
		khajep-atp-overlay.dtbo \
		khajep-qrd-overlay.dtbo \
		khajep-qrd-hvdcp3p5-overlay.dtbo \
		khajep-qrd-nowcd9375-overlay.dtbo \
		khajep-qrd-nopmi-overlay.dtbo \
		khajep-idp-overlay.dtbo \
		khajep-idp-nopmi-overlay.dtbo \
		khajep-idp-usbc-overlay.dtbo \
		khajep-idp-pm8010-overlay.dtbo \
		khajep-idps-display-90hz-overlay.dtbo \
		khajeq-atp-overlay.dtbo \
		khajeq-qrd-overlay.dtbo \
		khajeq-qrd-hvdcp3p5-overlay.dtbo \
		khajeq-qrd-nowcd9375-overlay.dtbo \
		khajeq-qrd-nopmi-overlay.dtbo \
		khajeq-idp-overlay.dtbo \
		khajeq-idp-nopmi-overlay.dtbo \
		khajeq-idp-usbc-overlay.dtbo \
		khajeq-idp-pm8010-overlay.dtbo \
		khajeq-idps-display-90hz-overlay.dtbo \
		khajeg-atp-overlay.dtbo \
		khajeg-qrd-overlay.dtbo \
		khajeg-qrd-hvdcp3p5-overlay.dtbo \
		khajeg-qrd-nowcd9375-overlay.dtbo \
		khajeg-qrd-nopmi-overlay.dtbo \
		khajeg-idp-overlay.dtbo \
		khajeg-idp-nopmi-overlay.dtbo \
		khajeg-idp-usbc-overlay.dtbo \
		khajeg-idp-pm8010-overlay.dtbo \
		khajeg-idps-display-90hz-overlay.dtbo

khaje-atp-overlay.dtbo-base := khaje.dtb
khaje-idp-overlay.dtbo-base := khaje.dtb
khaje-idp-nopmi-overlay.dtbo-base := khaje.dtb
khaje-idp-usbc-overlay.dtbo-base := khaje.dtb
khaje-idp-pm8010-overlay.dtbo-base := khaje.dtb
khaje-idps-display-90hz-overlay.dtbo-base := khaje.dtb
khaje-qrd-overlay.dtbo-base := khaje.dtb
khaje-qrd-hvdcp3p5-overlay.dtbo-base := khaje.dtb
khaje-qrd-nopmi-overlay.dtbo-base := khaje.dtb
khaje-qrd-nowcd9375-overlay.dtbo-base := khaje.dtb
khajep-atp-overlay.dtbo-base := khajep.dtb
khajep-idps-display-90hz-overlay.dtbo-base := khajep.dtb
khajep-idp-overlay.dtbo-base := khajep.dtb
khajep-idp-nopmi-overlay.dtbo-base := khajep.dtb
khajep-idp-usbc-overlay.dtbo-base := khajep.dtb
khajep-idp-pm8010-overlay.dtbo-base := khajep.dtb
khajep-qrd-overlay.dtbo-base := khajep.dtb
khajep-qrd-hvdcp3p5-overlay.dtbo-base := khajep.dtb
khajep-qrd-nowcd9375-overlay.dtbo-base := khajep.dtb
khajep-qrd-nopmi-overlay.dtbo-base := khajep.dtb
khajeq-atp-overlay.dtbo-base := khajeq.dtb
khajeq-qrd-overlay.dtbo-base := khajeq.dtb
khajeq-qrd-hvdcp3p5-overlay.dtbo-base := khajeq.dtb
khajeq-qrd-nowcd9375-overlay.dtbo-base := khajeq.dtb
khajeq-qrd-nopmi-overlay.dtbo-base := khajeq.dtb
khajeq-idps-display-90hz-overlay.dtbo-base := khajeq.dtb
khajeq-idp-overlay.dtbo-base := khajeq.dtb
khajeq-idp-nopmi-overlay.dtbo-base := khajeq.dtb
khajeq-idp-pm8010-overlay.dtbo-base := khajeq.dtb
khajeq-idp-usbc-overlay.dtbo-base := khajeq.dtb
khajeg-atp-overlay.dtbo-base := khajeg.dtb
khajeg-qrd-overlay.dtbo-base := khajeg.dtb
khajeg-qrd-hvdcp3p5-overlay.dtbo-base := khajeg.dtb
khajeg-qrd-nowcd9375-overlay.dtbo-base := khajeg.dtb
khajeg-qrd-nopmi-overlay.dtbo-base := khajeg.dtb
khajeg-idp-overlay.dtbo-base := khajeg.dtb
khajeg-idp-nopmi-overlay.dtbo-base := khajeg.dtb
khajeg-idp-pm8010-overlay.dtbo-base := khajeg.dtb
khajeg-idp-usbc-overlay.dtbo-base := khajeg.dtb
khajeg-idps-display-90hz-overlay.dtbo-base := khajeg.dtb
else
dtb-$(CONFIG_ARCH_KHAJE) += khaje-idp.dtb \
		khaje-qrd.dtb \
		khaje-qrd-hvdcp3p5.dtb \
		khaje-qrd-nowcd9375.dtb \
		khaje-idp-nopmi.dtb \
		khaje-idp-usbc.dtb \
		khaje-idp-pm8010.dtb \
		khaje-qrd-nopmi.dtb \
		khaje-idps-display-90hz.dtb \
		khaje-atp.dtb \
		khajep-atp.dtb \
		khajep-qrd.dtb \
		khajep-qrd-hvdcp3p5.dtb \
		khajep-idps-display-90hz.dtb \
		khajep-idp-nopmi.dtb \
		khajep-idp-usbc.dtb \
		khajep-idp-pm8010.dtb \
		khajep-qrd-nowcd9375.dtb \
		khajep-qrd-nopmi.dtb \
		khajeq-atp.dtb \
		khajeq-idps-display-90hz.dtb \
		khajeq-idp-nopmi.dtb \
		khajeq-idp-usbc.dtb \
		khajeq-idp-pm8010.dtb \
		khajeq-qrd.dtb \
		khajeq-qrd-nowcd9375.dtb \
		khajeq-qrd-hvdcp3p5.dtb \
		khajeq-qrd-nopmi.dtb \
		khajeg-atp.dtb \
		khajeg-qrd.dtb \
		khajeg-qrd-nowcd9375.dtb \
		khajeg-qrd-hvdcp3p5.dtb \
		khajeg-qrd-nopmi.dtb \
		khajeg-idp.dtb \
		khajeg-idp-nopmi.dtb \
		khajeg-idp-usbc.dtb \
		khajeg-idp-pm8010.dtb \
		khajeg-idps-display-90hz.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SDM660) += \
                sdm660-mtp-external-codec-overlay.dtbo \
                sdm660-mtp-internal-codec-overlay.dtbo \
                sdm660-cdp-external-codec-overlay.dtbo \
                sdm660-cdp-internal-codec-overlay.dtbo \
                sdm660-qrd-external-codec-overlay.dtbo \
                sdm660-qrd-dsi-rm67195-amoled-overlay.dtbo \
                sdm660-rcm-external-codec-overlay.dtbo \
                sdm660-rcm-internal-codec-overlay.dtbo \
                sda660-mtp-external-codec-overlay.dtbo \
                sda660-cdp-external-codec-overlay.dtbo \
                sda660-rcm-external-codec-overlay.dtbo

sdm660-mtp-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-mtp-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-cdp-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-cdp-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-qrd-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-qrd-dsi-rm67195-amoled-overlay.dtbo-base := sdm660-pm660a.dtb

sdm660-rcm-external-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sdm660-rcm-internal-codec-overlay.dtbo-base := sdm660-pm660l.dtb

sda660-mtp-external-codec-overlay.dtbo-base := sda660-pm660l.dtb

sda660-cdp-external-codec-overlay.dtbo-base := sda660-pm660l.dtb

sda660-rcm-external-codec-overlay.dtbo-base := sda660-pm660l.dtb
else
dtb-$(CONFIG_ARCH_SDM660) += sdm660-sim.dtb \
sdm660-internal-codec-cdp.dtb \
        sdm660-internal-codec-mtp.dtb \
        sdm660-internal-codec-rcm.dtb \
        sdm660-cdp.dtb \
        sdm660-mtp.dtb \
        sdm660-qrd.dtb \
        sdm660-rcm.dtb \
        sdm660-pm660a-cdp.dtb \
        sdm660-pm660a-mtp.dtb \
        sdm660-pm660a-qrd.dtb \
        sdm660-pm660a-rcm.dtb \
        sdm660-internal-codec-pm660a-cdp.dtb \
        sdm660-internal-codec-pm660a-mtp.dtb \
        sdm660-internal-codec-pm660a-rcm.dtb \
        sdm660-pm660a-sim.dtb \
        sda660-cdp.dtb \
        sda660-mtp.dtb \
        sda660-rcm.dtb \
        sda660-pm660a-cdp.dtb \
        sda660-pm660a-mtp.dtb \
        sda660-pm660a-rcm.dtb \
        sda660-pm660a-qrd-hdk.dtb \
        sdm660-headset-jacktype-no-cdp.dtb \
        sdm660-headset-jacktype-no-rcm.dtb \
        sdm660-pm660a-headset-jacktype-no-cdp.dtb \
        sdm660-pm660a-headset-jacktype-no-rcm.dtb \
        sdm660-usbc-audio-mtp.dtb \
        sdm660-usbc-audio-rcm.dtb \
	sdm660-qrd-dsi-rm67195-amoled.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)

dtbo-$(CONFIG_ARCH_SDM439) += sdm439-mtp-overlay.dtbo \
        sdm439-cdp-overlay.dtbo \
        sdm439-qrd-overlay.dtbo \
        sdm439-external-codec-mtp-overlay.dtbo \
        sdm439-rcm-overlay.dtbo

dtbo-$(CONFIG_ARCH_SDM429) += sdm429-mtp-overlay.dtbo \
	sdm429-cdp-overlay.dtbo \
	sdm429-qrd-overlay.dtbo

dtbo-$(CONFIG_ARCH_QM215) +=qm215-qrd-overlay.dtbo \
	qcm2150-qrd-overlay.dtbo \
	qm215-qrd-smb1360-overlay.dtbo

sdm439-mtp-overlay.dtbo-base := sdm439.dtb \
	sda439.dtb \
	msm8937-interposer-sdm439.dtb

sdm439-cdp-overlay.dtbo-base := sdm439.dtb \
        sda439.dtb \
        msm8937-interposer-sdm439.dtb

sdm439-qrd-overlay.dtbo-base := sdm439.dtb \
        msm8937-interposer-sdm439.dtb

sdm439-external-codec-mtp-overlay.dtbo-base := sdm439.dtb
sdm439-rcm-overlay.dtbo-base := sdm439.dtb


sdm429-mtp-overlay.dtbo-base := sdm429.dtb \
	sda429.dtb \
	msm8937-interposer-sdm429.dtb

sdm429-cdp-overlay.dtbo-base := sdm429.dtb \
	sda429.dtb \
	msm8937-interposer-sdm429.dtb

sdm429-qrd-overlay.dtbo-base := sdm429.dtb \
	msm8937-interposer-sdm429.dtb

qm215-qrd-overlay.dtbo-base := qm215.dtb
qcm2150-qrd-overlay.dtbo-base := qcm2150.dtb
qm215-qrd-smb1360-overlay.dtbo-base := qm215.dtb
else
dtb-$(CONFIG_ARCH_SDM439) += sdm439-mtp.dtb \
	sdm439-cdp.dtb \
	sdm439-qrd.dtb \
	sda439-mtp.dtb \
	sda439-cdp.dtb \
	sdm439-external-codec-mtp.dtb \
	sdm439-rcm.dtb
dtb-$(CONFIG_ARCH_QM215) += qm215-qrd.dtb \
	qcm2150-qrd.dtb \
	qm215-qrd-smb1360.dtb

dtb-$(CONFIG_ARCH_SDM429) += sdm429-mtp.dtb \
	sdm429-cdp.dtb \
	sdm429-qrd.dtb \
	sda429-mtp.dtb \
	sda429-cdp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_HOLI) += holi-rumi-overlay.dtbo \
	holi-mtp-overlay.dtbo \
	holi-cdp-overlay.dtbo \
	holi-cdp-lcd-overlay.dtbo \
	holi-qrd-overlay.dtbo \
	holi-atp-overlay.dtbo \
	holi-mtp-usbc-overlay.dtbo \
	holi-mtp-pm6125-overlay.dtbo \
	holi-cdp-pm6125-overlay.dtbo \
	holi-cdp-lcd-pm6125-overlay.dtbo \
	holi-mtp-usbc-pm6125-overlay.dtbo \
	holi-mtp-pm6125-nopmi-overlay.dtbo \
	holi-qrd-pm6125-overlay.dtbo \
	holi-qrd-pm6125-nopmi-overlay.dtbo

holi-rumi-overlay.dtbo-base := holi.dtb
holi-mtp-overlay.dtbo-base := holi.dtb
holi-cdp-overlay.dtbo-base := holi.dtb
holi-cdp-lcd-overlay.dtbo-base := holi.dtb
holi-qrd-overlay.dtbo-base := holi.dtb
holi-atp-overlay.dtbo-base := holi.dtb
holi-mtp-usbc-overlay.dtbo-base := holi.dtb
holi-mtp-pm6125-overlay.dtbo-base := holi.dtb
holi-cdp-pm6125-overlay.dtbo-base := holi.dtb
holi-cdp-lcd-pm6125-overlay.dtbo-base := holi.dtb
holi-mtp-usbc-pm6125-overlay.dtbo-base := holi.dtb
holi-mtp-pm6125-nopmi-overlay.dtbo-base := holi.dtb
holi-qrd-pm6125-overlay.dtbo-base := holi.dtb
holi-qrd-pm6125-nopmi-overlay.dtbo-base := holi.dtb

else
dtb-$(CONFIG_ARCH_HOLI) += holi-rumi.dtb \
	holi-mtp.dtb \
	holi-cdp.dtb \
	holi-cdp-lcd.dtb \
	holi-qrd.dtb \
	holi-atp.dtb \
	holi-mtp-usbc.dtb\
	holi-mtp-pm6125.dtb \
	holi-cdp-pm6125.dtb \
	holi-cdp-lcd-pm6125.dtb \
	holi-mtp-usbc-pm6125.dtb \
	holi-mtp-pm6125-nopmi.dtb \
	holi-qrd-pm6125.dtb \
	holi-qrd-pm6125-nopmi.dtb

endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_BLAIR) += blair-rumi-overlay.dtbo \
	blair-mtp-overlay.dtbo \
	blair-cdp-overlay.dtbo \
	blair-atp-overlay.dtbo \
	blair-qrd-overlay.dtbo \
	blair-mtp-usbc-overlay.dtbo \
	blair-mtp-nopmi-overlay.dtbo \
	blair-qrd-nopmi-overlay.dtbo \
	blairp-mtp-overlay.dtbo \
	blairp-cdp-overlay.dtbo \
	blairp-atp-overlay.dtbo \
	blairp-qrd-overlay.dtbo \
	blairp-mtp-usbc-overlay.dtbo \
	blairp-mtp-nopmi-overlay.dtbo \
	blairp-qrd-nopmi-overlay.dtbo

blair-rumi-overlay.dtbo-base := blair.dtb
blair-mtp-overlay.dtbo-base := blair.dtb
blair-cdp-overlay.dtbo-base := blair.dtb
blair-atp-overlay.dtbo-base := blair.dtb
blair-qrd-overlay.dtbo-base := blair.dtb
blair-mtp-usbc-overlay.dtbo-base := blair.dtb
blair-mtp-nopmi-overlay.dtbo-base := blair.dtb
blair-qrd-nopmi-overlay.dtbo-base := blair.dtb
blairp-mtp-overlay.dtbo-base := blairp.dtb
blairp-cdp-overlay.dtbo-base := blairp.dtb
blairp-atp-overlay.dtbo-base := blairp.dtb
blairp-qrd-overlay.dtbo-base := blairp.dtb
blairp-mtp-usbc-overlay.dtbo-base := blairp.dtb
blairp-mtp-nopmi-overlay.dtbo-base := blairp.dtb
blairp-qrd-nopmi-overlay.dtbo-base := blairp.dtb
else
dtb-$(CONFIG_ARCH_BLAIR) += blair-rumi.dtb \
	blair-mtp.dtb \
	blair-cdp.dtb \
	blair-atp.dtb \
	blair-qrd.dtb \
	blair-mtp-usbc.dtb \
	blair-mtp-nopmi.dtb \
	blair-qrd-nopmi.dtb \
	blairp-mtp.dtb \
	blairp-cdp.dtb \
	blairp-atp.dtb \
	blairp-qrd.dtb \
	blairp-mtp-usbc.dtb \
	blairp-mtp-nopmi.dtb \
	blairp-qrd-nopmi.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_SHIMA) +=    \
	shima-rumi-overlay.dtbo \
	shima-idp-overlay.dtbo  \
	shima-idp-120fps-overlay.dtbo \
	shima-atp-overlay.dtbo \
	shima-qrd-overlay.dtbo \
	shima-idps-digital-mics-overlay.dtbo \
	shima-idps-digital-mics-120fps-overlay.dtbo

shima-rumi-overlay.dtbo-base := shima.dtb
shima-idp-overlay.dtbo-base := shima.dtb
shima-idp-120fps-overlay.dtbo-base := shima.dtb
shima-atp-overlay.dtbo-base := shima.dtb
shima-qrd-overlay.dtbo-base := shima.dtb
shima-idps-digital-mics-overlay.dtbo-base := shima.dtb
shima-idps-digital-mics-120fps-overlay.dtbo-base := shima.dtb
else
dtb-$(CONFIG_ARCH_SHIMA) += shima-rumi.dtb  \
			    shima-idp.dtb   \
			    shima-idp-120fps.dtb  \
			    shima-atp.dtb \
			    shima-qrd.dtb \
			    shima-idps-digital-mics.dtb \
			    shima-idps-digital-mics-120fps.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_YUPIK) +=    \
	yupik-rumi-overlay.dtbo \
	yupik-idp-overlay.dtbo \
	yupik-atp-overlay.dtbo \
	yupik-qrd-overlay.dtbo \
	yupik-idps-amoled-overlay.dtbo \
	yupik-idp-pm7250b-overlay.dtbo \
	yupik-idp-hsp-overlay.dtbo \
	yupikp-idp-overlay.dtbo \
	yupikp-atp-overlay.dtbo \
	yupikp-qrd-overlay.dtbo \
	yupikp-idps-amoled-overlay.dtbo \
	yupikp-idp-hsp-overlay.dtbo \
	yupik-iot-idp-overlay.dtbo \
	yupik-iot-idp-pm7250b-overlay.dtbo \
	yupik-iot-qrd-overlay.dtbo \
	yupik-iot-hsp-overlay.dtbo \
	yupik-iot-hsp-pm7250b-overlay.dtbo \
	katmai-hsp-overlay.dtbo \
	katmai-hsp-pm7250b-overlay.dtbo \
	katmai-fp2-hsp-overlay.dtbo \
	katmai-fp2-hsp-pm7250b-overlay.dtbo \
	yupik-iot-idps-amoled-overlay.dtbo \
	yupikp-iot-idp-overlay.dtbo \
	yupikp-iot-idp-pm7250b-overlay.dtbo \
	yupikp-iot-qrd-overlay.dtbo \
	yupikp-iot-hsp-overlay.dtbo \
	yupikp-iot-hsp-pm7250b-overlay.dtbo \
	katmaip-hsp-overlay.dtbo \
	katmaip-hsp-pm7250b-overlay.dtbo \
	katmaip-fp2-hsp-overlay.dtbo \
	katmaip-fp2-hsp-pm7250b-overlay.dtbo \
	yupikp-iot-idps-amoled-overlay.dtbo


yupik-rumi-overlay.dtbo-base := yupik.dtb
yupik-idp-overlay.dtbo-base := yupik.dtb
yupik-atp-overlay.dtbo-base := yupik.dtb
yupik-qrd-overlay.dtbo-base := yupik.dtb
yupik-idps-amoled-overlay.dtbo-base := yupik.dtb
yupik-idp-pm7250b-overlay.dtbo-base := yupik.dtb
yupik-idp-hsp-overlay.dtbo-base := yupik-hsp.dtb
yupikp-idp-overlay.dtbo-base := yupikp.dtb
yupikp-atp-overlay.dtbo-base := yupikp.dtb
yupikp-qrd-overlay.dtbo-base := yupikp.dtb
yupikp-idps-amoled-overlay.dtbo-base := yupikp.dtb
yupikp-idp-hsp-overlay.dtbo-base := yupikp-hsp.dtb
yupik-iot-idp-overlay.dtbo-base := yupik-iot.dtb katmai.dtb katmai-fp2.dtb
yupik-iot-idp-pm7250b-overlay.dtbo-base := yupik-iot.dtb katmai.dtb katmai-fp2.dtb
yupik-iot-qrd-overlay.dtbo-base := yupik-iot.dtb katmai.dtb katmai-fp2.dtb
yupik-iot-hsp-overlay.dtbo-base := yupik-iot.dtb
yupik-iot-hsp-pm7250b-overlay.dtbo-base := yupik-iot.dtb
katmai-hsp-overlay.dtbo-base :=  katmai.dtb
katmai-hsp-pm7250b-overlay.dtbo-base :=  katmai.dtb
katmai-fp2-hsp-overlay.dtbo-base :=  katmai-fp2.dtb
katmai-fp2-hsp-pm7250b-overlay.dtbo-base :=  katmai-fp2.dtb
yupik-iot-idps-amoled-overlay.dtbo-base := yupik-iot.dtb katmai.dtb katmai-fp2.dtb
yupikp-iot-idp-overlay.dtbo-base := yupikp-iot.dtb katmaip.dtb katmaip-fp2.dtb
yupikp-iot-idp-pm7250b-overlay.dtbo-base := yupikp-iot.dtb katmaip.dtb katmaip-fp2.dtb
yupikp-iot-qrd-overlay.dtbo-base := yupikp-iot.dtb katmaip.dtb katmaip-fp2.dtb
yupikp-iot-hsp-overlay.dtbo-base := yupikp-iot.dtb
yupikp-iot-hsp-pm7250b-overlay.dtbo-base := yupikp-iot.dtb
katmaip-hsp-overlay.dtbo-base := katmaip.dtb
katmaip-hsp-pm7250b-overlay.dtbo-base := katmaip.dtb
katmaip-fp2-hsp-overlay.dtbo-base := katmaip-fp2.dtb
katmaip-fp2-hsp-pm7250b-overlay.dtbo-base := katmaip-fp2.dtb
yupikp-iot-idps-amoled-overlay.dtbo-base := yupikp-iot.dtb katmaip.dtb katmaip-fp2.dtb
else
dtb-$(CONFIG_ARCH_YUPIK) += yupik-rumi.dtb \
	yupik-idp.dtb \
	yupik-atp.dtb \
	yupik-qrd.dtb \
	yupik-idps-amoled.dtb \
	yupik-idp-pm7250b.dtb \
	yupik-idp-hsp.dtb \
	yupikp-idp.dtb \
	yupikp-atp.dtb \
	yupikp-qrd.dtb \
	yupikp-idps-amoled.dtb \
	yupikp-idp-hsp.dtb \
	yupik-iot-idp.dtb \
	yupik-iot-idp-pm7250b.dtb \
	yupik-iot-qrd.dtb \
	yupik-iot-hsp.dtb \
	yupik-iot-idps-amoled.dtb \
	yupikp-iot-idp.dtb \
	yupikp-iot-idp-pm7250b.dtb \
	yupikp-iot-qrd.dtb \
	yupikp-iot-hsp.dtb \
	yupik-iot-hsp-pm7250b.dtb \
	yupikp-iot-hsp-pm7250b.dtb \
	yupikp-iot-idps-amoled.dtb \
	katmai-idp.dtb \
	katmai-idp-pm7250b.dtb \
	katmai-qrd.dtb \
	katmai-hsp.dtb \
	katmai-idps-amoled.dtb \
	katmaip-idp.dtb \
	katmaip-idp-pm7250b.dtb \
	katmaip-qrd.dtb \
	katmaip-hsp.dtb \
	katmai-hsp-pm7250b.dtb \
	katmaip-hsp-pm7250b.dtb \
	katmaip-idps-amoled.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
dtbo-$(CONFIG_ARCH_MONACO) +=    \
	monaco-rumi-overlay.dtbo \
	monaco-standalone-idp-v1-overlay.dtbo \
	monaco-standalone-idp-v2-overlay.dtbo \
	monaco-standalone-idp-v3-overlay.dtbo \
	monaco-idp-v1-overlay.dtbo \
	monaco-idp-v2-overlay.dtbo \
	monaco-idp-v3-overlay.dtbo

monaco-rumi-overlay.dtbo-base := monaco.dtb
monaco-standalone-idp-v1-overlay.dtbo-base := monaco.dtb
monaco-standalone-idp-v2-overlay.dtbo-base := monaco.dtb
monaco-standalone-idp-v3-overlay.dtbo-base := monaco.dtb
monaco-idp-v1-overlay.dtbo-base := monaco.dtb monacop.dtb
monaco-idp-v2-overlay.dtbo-base := monaco.dtb
monaco-idp-v3-overlay.dtbo-base := monaco.dtb

else
dtb-$(CONFIG_ARCH_MONACO) += monaco-rumi.dtb \
	monaco-standalone-idp-v1.dtb \
	monaco-standalone-idp-v2.dtb \
	monaco-standalone-idp-v3.dtb \
	monaco-idp-v1.dtb \
	monaco-idp-v2.dtb \
	monaco-idp-v3.dtb \
	monacop-idp-v1.dtb
endif

dtb-$(CONFIG_ARCH_SCUBA) += qrb2210-rb1.dtb

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
ifeq ($(CONFIG_AUTO_LXC_OVERLAY), y)
	dtbo-$(CONFIG_ARCH_SA8155) += \
		sa8155-adp-star-lxc-overlay.dtbo \
		sa8155p-adp-star-lxc-overlay.dtbo \
		sa8155-v2-adp-air-lxc-overlay.dtbo \
		sa8155p-v2-adp-air-lxc-overlay.dtbo
else
	dtbo-$(CONFIG_ARCH_SA8155) += \
		sa8155-adp-star-overlay.dtbo \
		sa8155p-adp-star-overlay.dtbo \
		sa8155-v2-adp-air-overlay.dtbo \
		sa8155p-v2-adp-air-overlay.dtbo
endif

sa8155-adp-star-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-adp-star-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-v2-adp-air-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-v2-adp-air-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-adp-star-lxc-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-adp-star-lxc-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
sa8155-v2-adp-air-lxc-overlay.dtbo-base := sa8155.dtb sa8155-v2.dtb
sa8155p-v2-adp-air-lxc-overlay.dtbo-base := sa8155p.dtb sa8155p-v2.dtb
else
dtb-$(CONFIG_ARCH_SA8155)       += sa8155-adp-star.dtb \
	sa8155p-adp-star.dtb \
	sa8155-v2-adp-star.dtb \
	sa8155p-v2-adp-star.dtb \
	sa8155-v2-adp-air.dtb \
	sa8155p-v2-adp-air.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
ifeq ($(CONFIG_AUTO_LXC_OVERLAY), y)
	dtbo-$(CONFIG_ARCH_SA6155) += \
		sa6155p-adp-star-lxc-overlay.dtbo \
		sa6155p-v2-adp-star-lxc-overlay.dtbo \
		sa6155p-adp-air-lxc-overlay.dtbo \
		sa6155p-v2-adp-air-lxc-overlay.dtbo
else
	dtbo-$(CONFIG_ARCH_SA6155) += \
		sa6155-adp-star-overlay.dtbo \
		sa6155p-adp-star-overlay.dtbo \
		sa6155p-adp-star-lpass-overlay.dtbo \
		sa6155-adp-air-overlay.dtbo \
		sa6155p-adp-air-overlay.dtbo \
		sa6155p-v2-adp-star-overlay.dtbo \
		sa6155p-v2-adp-air-overlay.dtbo \
		sa6155p-v2-adp-air-lpass-overlay.dtbo
endif

sa6155-adp-star-overlay.dtbo-base := sa6155.dtb
sa6155p-adp-star-overlay.dtbo-base := sa6155p.dtb
sa6155p-adp-star-lpass-overlay.dtbo-base :=sa6155p.dtb
sa6155p-v2-adp-star-overlay.dtbo-base := sa6155p.dtb
sa6155-adp-air-overlay.dtbo-base := sa6155.dtb
sa6155p-adp-air-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-air-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-air-lpass-overlay.dtbo-base := sa6155p.dtb
sa6155p-adp-star-lxc-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-star-lxc-overlay.dtbo-base := sa6155p.dtb
sa6155p-adp-air-lxc-overlay.dtbo-base := sa6155p.dtb
sa6155p-v2-adp-air-lxc-overlay.dtbo-base := sa6155p.dtb
else
dtb-$(CONFIG_ARCH_SA6155)       += sa6155-adp-star.dtb \
	sa6155p-adp-star.dtb \
	sa6155p-adp-star-lpass.dtb \
	sa6155-adp-air.dtb \
	sa6155p-adp-air.dtb \
	sa6155p-v2-adp-star.dtb \
	sa6155p-v2-adp-air.dtb \
	sa6155p-v2-adp-air-lpass.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
ifeq ($(CONFIG_AUTO_LXC_OVERLAY), y)
	dtbo-$(CONFIG_ARCH_SA8195) += \
		sa8195p-adp-star-lxc-overlay.dtbo \
		sa8195p-v2-adp-air-lxc-overlay.dtbo
else
	dtbo-$(CONFIG_ARCH_SA8195) += \
		sa8195p-adp-star-overlay.dtbo \
		sa8195p-v2-adp-air-overlay.dtbo
endif

sa8195p-adp-star-overlay.dtbo-base := sa8195p.dtb
sa8195p-v2-adp-air-overlay.dtbo-base := sa8195p.dtb
sa8195p-adp-star-lxc-overlay.dtbo-base := sa8195p.dtb
sa8195p-v2-adp-air-lxc-overlay.dtbo-base := sa8195p.dtb
else
dtb-$(CONFIG_ARCH_SA8195)	+= sa8195p-adp-star.dtb \
	sa8195p-v2-adp-air.dtb
endif

dtb-$(CONFIG_ARCH_SA2150P) += sa2150p-ccard-emmc.dtb
endif

ifeq ($(CONFIG_ARCH_LAHAINA), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += lahaina-vm-mtp.dtb \
	lahaina-vm-cdp.dtb \
	lahaina-vm-qrd.dtb \
	lahaina-vm-mtp-v2.dtb \
	lahaina-vm-mtp-v2.1.dtb
endif
endif

dtb-$(CONFIG_ARCH_SDXLEMUR) += sdxlemur-rumi.dtb \
	sdxlemur-atp.dtb \
	sdxlemur-cdp.dtb \
	sdxlemur-mtp.dtb \
	sdxlemur-mtp-mbb.dtb \
	sdxlemur-mtp-cpe.dtb \
	sdxlemur-mtp-cpe-pine1x.dtb \
	sdxlemur-mtp-cpe-pine2x.dtb \
	sdxlemur-mtp-mbb-emmc.dtb \
	sdxlemur-mtp-mbb-emmc-512mb.dtb \
	sdxlemur-mtp-mbb-ntn3-pcie.dtb \
	sdxlemur-mtp-mbb-pcie-ep.dtb \
	sdxlemur-mtp-mbb-pcie-ep-ipq.dtb \
	sdxlemur-mtp-mbb-pcie-rc-ep.dtb \
	sdxlemur-mtp-mbb-m2-ep.dtb \
	sdxlemur-mtp-mbb-m2-ep-usb.dtb \
	sdxlemur-mtp-mbb.dtb \
	sdxlemur-rcm-pcie-ep.dtb \
	sdxlemur-rcm-rc.dtb \
	sdxlemur-rcm-rc-pine1x.dtb \
	sdxlemur-rcm-rc-pine2x.dtb \
	sdxlemur-v2-cdp.dtb \
	sdxlemur-v2-mtp-mbb.dtb \
	sdxlemur-v2-mtp-cpe.dtb \
	sdxlemur-v2-mtp-mbb-emmc.dtb \
	sdxlemur-v2-mtp-mbb-ntn3-pcie.dtb \
	sdxlemur-v2-mtp-mbb-pcie-ep.dtb \
	sdxlemur-v2-mtp-mbb-pcie-ep-ipq.dtb \
	sdxlemur-v2-mtp-mbb-pcie-rc-ep.dtb \
	sdxlemur-v2-rcm-pcie-ep.dtb \
	sdxlemur-v2-rcm-rc.dtb \
	sdxlemur-v2-atp.dtb \
	sdxlemur-v2-mtp-cpe-pine1x.dtb \
	sdxlemur-v2-mtp-cpe-pine2x.dtb \
	sdxlemur-v2-mtp-mbb-emmc-512mb.dtb \
	sdxlemur-v2-mtp-mbb-m2-ep-usb.dtb \
	sdxlemur-v2-mtp-mbb-m2-ep.dtb \
	sdxlemur-v2-rcm-rc-pine1x.dtb \
	sdxlemur-v2-rcm-rc-pine2x.dtb \
	sdxlemur-v2-m2-ep-fwa.dtb \
	sdxlemur-v2-mtp-cpe-pine2x-5+6.dtb



ifeq ($(CONFIG_ARCH_SHIMA), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += shima-vm-rumi.dtb \
	shima-vm-atp.dtb \
	shima-vm-idp.dtb \
	shima-vm-qrd.dtb
endif
endif

dtb-$(CONFIG_ARCH_SDXNIGHTJAR) += sdxnightjar-mtp.dtb \
	sdxnightjar-cdp.dtb \
	sdxnightjar-qrd.dtb \
	sdxnightjar-dualwifi-mtp.dtb \
	sdxnightjar-512mb-mtp.dtb \
	sdxnightjar-dualwifi-512mb-mtp.dtb

ifeq ($(CONFIG_ARCH_YUPIK), y)
ifeq ($(CONFIG_ARCH_QTI_VM), y)
dtb-$(CONFIG_ARCH_QTI_VM) += yupik-vm-rumi.dtb \
	yupik-vm-atp.dtb \
	yupik-vm-idp.dtb \
	yupik-vm-qrd.dtb
endif
endif

dtb-$(CONFIG_QTI_QUIN_GVM) += sa8155-vm-la.dtb \
	sa8155-vm-lv.dtb \
	sa8155-vm-la-mt.dtb \
	sa8155-vm-lv-mt.dtb \
	sa8195-vm-la.dtb \
	sa8195-vm-lv.dtb \
	sa8195-vm-la-mt.dtb \
	sa8195-vm-lv-mt.dtb \
	sa8195-vm-lv-lxc.dtb \
	sa6155p-vm-la.dtb \
	direwolf-vm-lv.dtb \
	direwolf-vm-la.dtb

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
	dtbo-$(CONFIG_ARCH_DIREWOLF) += direwolf-ivi-rumi-overlay.dtbo \
		direwolf-ivi-adp-star-overlay.dtbo \
		direwolf-adas-rumi-overlay.dtbo \
		direwolf-adas-adp-star-overlay.dtbo

direwolf-ivi-rumi-overlay.dtbo-base := direwolf-ivi.dtb
direwolf-ivi-adp-star-overlay.dtbo-base := direwolf-ivi.dtb
direwolf-adas-rumi-overlay.dtbo-base := direwolf-adas.dtb
direwolf-adas-adp-star-overlay.dtbo-base := direwolf-adas.dtb
else
dtb-$(CONFIG_ARCH_DIREWOLF) += direwolf-ivi-rumi.dtb \
	direwolf-ivi-adp-star.dtb \
	direwolf-adas-rumi.dtb \
	direwolf-adas-adp-star.dtb
endif

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb *.dtbo
