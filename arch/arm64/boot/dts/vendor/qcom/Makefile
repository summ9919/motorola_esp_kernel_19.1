# Only include Motorola DTBs
ifeq ($(CONFIG_MMI_DEVICE_DTBS),y)
ifneq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
$(error Moto DT w/o overlay is undefined!!!)
endif

# Motorola Device Trees
dtbo-$(CONFIG_ARCH_SAVANNAH) += \
		kona-savannah-evt1-overlay.dtbo \
		kona-savannah-evt2-overlay.dtbo

dtbo-$(CONFIG_ARCH_BURTON) += \
		kona-burton-evt1-overlay.dtbo \
		kona-burton-dvt1-overlay.dtbo \
		kona-burton-dvt1c-overlay.dtbo \
                kona-burton-dvt2a-overlay.dtbo \
                kona-burton-dvt2b-overlay.dtbo \
		kona-burton-pvt-overlay.dtbo \
		kona-burton_npi-evt1-overlay.dtbo \
		kona-burton_npi-dvt1-overlay.dtbo \
		kona-burton_npi-dvt1c-overlay.dtbo \
		kona-burton_npi-dvt2a-overlay.dtbo \
		kona-burton_npi-dvt2b-overlay.dtbo \
		kona-burton_npi-pvt-overlay.dtbo

kona-savannah-evt1-overlay.dtbo-base := kona-moto-base.dtb
kona-savannah-evt2-overlay.dtbo-base := kona-moto-base-v2.dtb
kona-burton-evt1-overlay.dtbo-base   := kona-moto-base-v2.dtb
kona-burton-dvt1-overlay.dtbo-base   := kona-moto-base-v2.dtb
kona-burton-dvt1c-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-burton-dvt2a-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-burton-dvt2b-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-burton-pvt-overlay.dtbo-base := kona-moto-base-v2.1.dtb
kona-burton_npi-evt1-overlay.dtbo-base  := kona-moto-base-v2.dtb
kona-burton_npi-dvt1-overlay.dtbo-base  := kona-moto-base-v2.dtb
kona-burton_npi-dvt1c-overlay.dtbo-base := kona-moto-base-v2.1.dtb
kona-burton_npi-dvt2a-overlay.dtbo-base := kona-moto-base-v2.1.dtb
kona-burton_npi-dvt2b-overlay.dtbo-base := kona-moto-base-v2.1.dtb
kona-burton_npi-pvt-overlay.dtbo-base   := kona-moto-base-v2.1.dtb

dtbo-$(CONFIG_NIO_DTB) += \
		kona-nio-evt1-overlay.dtbo
kona-nio-evt1-overlay.dtbo-base   := kona-moto-base-v2.1.dtb

dtbo-$(CONFIG_PSTAR_DTB) += \
		kona-pstar-evt1-overlay.dtbo \
		kona-pstar-dvt1-overlay.dtbo \
		kona-pstar-prc-dvt2-overlay.dtbo \
		kona-pstar-row-dvt2-overlay.dtbo \
		kona-pstar-prc-dvt2b-overlay.dtbo \
		kona-pstar-row-dvt2b-overlay.dtbo \
		kona-pstar-prc-pvt-overlay.dtbo \
		kona-pstar-india-pvt-overlay.dtbo \
		kona-pstar-row-pvt-overlay.dtbo

kona-pstar-evt1-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-dvt1-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-prc-dvt2-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-row-dvt2-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-prc-dvt2b-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-row-dvt2b-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-prc-pvt-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-row-pvt-overlay.dtbo-base   := kona-moto-base-v2.1.dtb
kona-pstar-india-pvt-overlay.dtbo-base   := kona-moto-base-v2.1.dtb

dtbo-$(CONFIG_SMITH_DTB) += \
		lito-smith-evt1-overlay.dtbo \
		lito-smith-evt2-overlay.dtbo \
		lito-smith-dvt1a-overlay.dtbo \
                lito-smith-dvt1a2-overlay.dtbo \
		lito-smith-dvt1b-overlay.dtbo \
		lito-smith-dvt1c-overlay.dtbo \
		lito-smith-dvt2-overlay.dtbo \
		lito-smith-pvt-overlay.dtbo

lito-smith-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-dvt1a-overlay.dtbo-base := lito-moto-base.dtb
lito-smith-dvt1a2-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt1b-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt1c-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-dvt2-overlay.dtbo-base := lito-moto-base-v2.dtb
lito-smith-pvt-overlay.dtbo-base := lito-moto-base-v2.dtb

dtbo-$(CONFIG_RACER_DTB) += \
		lito-racer-evt1-overlay.dtbo \
		lito-racer-evt2-overlay.dtbo \
		lito-racer-dvt1-overlay.dtbo

lito-racer-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-racer-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-racer-dvt1-overlay.dtbo-base := lito-moto-base.dtb

dtbo-$(CONFIG_NAIRO_DTB) += \
		lito-nairo-evt1-overlay.dtbo \
		lito-nairo-evt2-overlay.dtbo \
		lito-nairo-evt3-overlay.dtbo \
		lito-nairo-evt3-cap-overlay.dtbo \
		lito-nairo-dvt1-overlay.dtbo \
		lito-nairo-dvt1-cap-overlay.dtbo \
		lito-nairo-dvt1a-overlay.dtbo \
		lito-nairo-dvt1a-cap-overlay.dtbo \
		lito-nairo-dvt2-overlay.dtbo \
		lito-nairo-dvt2-cap-overlay.dtbo \
		lito-nairo-pvt-overlay.dtbo \
		lito-nairo-pvt-cap-overlay.dtbo

lito-nairo-evt1-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt2-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt3-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-evt3-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1a-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt1a-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt2-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-dvt2-cap-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-pvt-overlay.dtbo-base := lito-moto-base.dtb
lito-nairo-pvt-cap-overlay.dtbo-base := lito-moto-base.dtb

dtbo-$(CONFIG_KIEV_DTB) += \
		lagoon-kiev-evt1-overlay.dtbo \
		lagoon-kiev-jp-evt1-overlay.dtbo

lagoon-kiev-evt1-overlay.dtbo-base := lagoon-moto-base-kiev.dtb
lagoon-kiev-jp-evt1-overlay.dtbo-base := lagoon-moto-base-kiev.dtb

dtbo-$(CONFIG_BERLIN_DTB) += \
		lagoon-berlin-evt1-overlay.dtbo

lagoon-berlin-evt1-overlay.dtbo-base := lagoon-moto-base-berlin.dtb

dtbo-$(CONFIG_BERLNA_DTB) += \
		lagoon-berlna-evt1-overlay.dtbo

lagoon-berlna-evt1-overlay.dtbo-base := lagoon-moto-base-berlna.dtb

dtbo-$(CONFIG_KIEVV_DTB) += \
                lagoon-kievv-evt1-overlay.dtbo

lagoon-kievv-evt1-overlay.dtbo-base := lagoon-moto-base-kievv.dtb

dtbo-$(CONFIG_KYOTO_DTB) += lagoon-kyoto-evt1-overlay.dtbo

lagoon-kyoto-evt1-overlay.dtbo-base := lagoon-moto-base-kyoto.dtb

else
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
        qrb5165-iot-rb5.dtb \
        qrb5165n-iot-rb5.dtb \
        kona-v2.1-iot-rb5.dtb
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
endif  # CONFIG_MMI_DEVICE_DTBS

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
		scuba-iot-qrd-non-eldo-overlay.dtbo

scuba-rumi-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-qrd-non-eldo-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-idp-usbc-overlay.dtbo-base := scuba.dtb scubap.dtb scuba-2gb.dtb
scuba-iot-idp-overlay.dtbo-base := scuba-iot.dtb scuba-iot-2gb.dtb scubap-iot.dtb scubap-iot-idp.dtb scubap-iot-idp-2gb.dtb
scuba-iot-qrd-eldo-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
scuba-iot-qrd-non-eldo-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
scuba-iot-idp-usbc-overlay.dtbo-base := scuba-iot.dtb scubap-iot.dtb scuba-iot-2gb.dtb
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
	scubap-iot-idp-2gb.dtb \
	scuba-iot-idp-2gb.dtb \
	scuba-iot-idp-usbc-2gb.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_KHAJE) += \
		khaje-idp-overlay.dtbo \
		khaje-qrd-overlay.dtbo \
		khaje-qrd-hvdcp3p5-overlay.dtbo \
		khaje-qrd-nowcd9375-overlay.dtbo \
		khaje-idp-nopmi-overlay.dtbo \
		khaje-idp-usbc-overlay.dtbo \
		khaje-idp-pm8010-overlay.dtbo \
		khaje-qrd-nopmi-overlay.dtbo \
		khaje-idps-display-90hz-overlay.dtbo \
		khaje-atp-overlay.dtbo

khaje-idp-overlay.dtbo-base := khaje.dtb
khaje-qrd-overlay.dtbo-base := khaje.dtb
khaje-qrd-hvdcp3p5-overlay.dtbo-base := khaje.dtb
khaje-qrd-nowcd9375-overlay.dtbo-base := khaje.dtb
khaje-idp-nopmi-overlay.dtbo-base := khaje.dtb
khaje-idp-usbc-overlay.dtbo-base := khaje.dtb
khaje-idp-pm8010-overlay.dtbo-base := khaje.dtb
khaje-qrd-nopmi-overlay.dtbo-base := khaje.dtb
khaje-idps-display-90hz-overlay.dtbo-base := khaje.dtb
khaje-atp-overlay.dtbo-base := khaje.dtb
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
		khaje-atp.dtb
endif

ifeq ($(CONFIG_BUILD_ARM64_DT_OVERLAY),y)
        dtbo-$(CONFIG_ARCH_SDM660) += \
                sdm660-mtp-external-codec-overlay.dtbo \
                sdm660-mtp-internal-codec-overlay.dtbo \
                sdm660-cdp-external-codec-overlay.dtbo \
                sdm660-cdp-internal-codec-overlay.dtbo \
                sdm660-qrd-external-codec-overlay.dtbo \
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
        sdm660-usbc-audio-rcm.dtb
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

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files    := *.dtb *.dtbo
