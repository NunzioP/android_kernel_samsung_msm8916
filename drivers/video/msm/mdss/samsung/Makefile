#
# Samsung Common file.
#
obj-y += ss_dsi_panel_common.o
obj-y += ss_dsi_mdnie_lite_common.o
obj-y += ss_dsi_smart_dimming_common.o
obj-$(CONFIG_SAMSUNG_DEBUG_DISPLAY) += dlog.o
#
# panel directory make file
#

# K, Kcat6 panel
obj-$(CONFIG_PANEL_S6E3FA2_AMS510CV01_FHD) += S6E3FA2_AMS510CV01/

# LENITS panel
obj-$(CONFIG_PANEL_S6E3HA0_AMS510CW01_WQHD) += S6E3HA0_AMS510CW01/

# TB panel
obj-$(CONFIG_PANEL_S6E3HF2_AMS559DE01_WQXGA) += S6E3HF2_AMS559DE01/

# U7 & K panel
obj-$(CONFIG_PANEL_EA8064G_AMS549EH03_FHD) += EA8064G_AMS549EH03/

# TR panel
obj-$(CONFIG_PANEL_S6E3HA2_AMS567DJ01_WQHD) += S6E3HA2_AMS567DJ01/

# A7 panel
obj-$(CONFIG_PANEL_S6E3FA2_AMS549EH01_FHD) += S6E3FA2_AMS549EH01/

# A5 panel /E5
obj-$(CONFIG_PANEL_EA8061V_AMS497EE01_HD) += EA8061V_AMS497EE01/

# A3 panel
obj-$(CONFIG_PANEL_S6E88A0_AMS452EF01_QHD) += S6E88A0_AMS452EF01/

# SERRANOVE panel
obj-$(CONFIG_PANEL_S6E88A0_AMS427AP24_QHD) += S6E88A0_AMS427AP24/

# ZERO_Q panel
obj-$(CONFIG_PANEL_S6E3HF2_AMB509EG01_WQHD) += S6E3HF2_AMB509EG01/

# Note8 panel
obj-$(CONFIG_PANEL_NT71391_BP080WX7_WXGA) += NT71391_BP080WX7/

# gt58 panel-S6D7AA0_LSL080AL03
obj-$(CONFIG_PANEL_S6D7AA0_LSL080AL03_WXGA) += S6D7AA0_LSL080AL03/

# E7 panel
obj-$(CONFIG_PANEL_EA8061_HD) += EA8061_AMS549BU19/ EA8061_AMS549BU19_ID400418/

# ZERO_Q_F panel
obj-$(CONFIG_PANEL_S6E3HA2_AMS509ES01_WQHD) += S6E3HA2_AMS509ES01/

# MILLET VE panel-S6D7AA0_LSL080AL03
obj-$(CONFIG_PANEL_S6D7AA0_LSL080AL03_RT8555_WXGA) += S6D7AA0_LSL080AL03_RT8555/

# Matisse VE panel-TC358764
obj-$(CONFIG_PANEL_TC358764_LTL101AL06_KTD3156_WXGA) += TC358764_LTL101AL06_KTD3156/

# DEGAS_VE panel-S6D7AA0_LSL080AL03
obj-$(CONFIG_PANEL_S6D7AA0_LSL080AL03_RT8511_WXGA) += S6D7AA0_LSL080AL03_RT8511/

#smart LTE display
obj-$(CONFIG_PANEL_VX5B3D_LTI550HN06_FHD) += VX5B3D_LTI550HN06/
obj-$(CONFIG_PANEL_VX5B3D_LTM215HT05_FHD) += VX5B3D_LTM215HT05/
obj-$(CONFIG_PANEL_VX5B3D_LTM184HL01_FHD) += VX5B3D_LTM184HL01/

# Rossa panel
obj-$(CONFIG_PANEL_SC7798A_BV045WVM_WVGA) += SC7798A_BV045WVM/
obj-$(CONFIG_PANEL_HX8369B_BV045WVM_WVGA) += HX8369B_BV045WVM/
obj-$(CONFIG_PANEL_S6D7AA0_LTL101AT01_WXGA) += S6D7AA0_LTL101AT01/

# FortunaTFN panel
obj-$(CONFIG_PANEL_HX8389C_GH9607501A_QHD) += HX8389C_GH9607501A/

# Fortuna second panel
obj-$(CONFIG_PANEL_S6D78A0_GH9607501A_QHD) += S6D78A0_GH9607501A/

# J1VZW_LL panel
obj-$(CONFIG_PANEL_S6D77A1A01_WVGA_VIDEO_PANEL) += S6D77A1A01_BV043WVMB1/
obj-$(CONFIG_PANEL_S6D77A1A01_WVGA_VIDEO_PANEL_REVB) += S6D77A1A01_BV043WVM/

# K5 panel
obj-$(CONFIG_PANEL_S6E3FA3_AMS499ER01_FHD) += S6E3FA3_AMS499ER01/

# H7 panel
obj-$(CONFIG_PANEL_S6E3FA3_AMS568HN01_FHD) += S6E3FA3_AMS568HN01/

#
# To build ALL panel files(For build error checking)
#
ifeq ($(CONFIG_DISPLAY_BUILD_ALL),y)
obj-y += S6E3FA2_AMS510CV01/
obj-y += S6E3HA0_AMS510CW01/
obj-y += S6E3HF2_AMS559DE01/
obj-y += EA8064G_AMS549EH03/
obj-y += S6E3HA2_AMS567DJ01/
obj-y += S6E3FA2_AMS549EH01/
obj-y += EA8061V_AMS497EE01/
obj-y += S6E88A0_AMS452EF01/
obj-y += S6E88A0_AMS427AP24/
obj-y += S6E3HF2_AMB509EG01/
obj-y += NT71391_BP080WX7/
obj-y += EA8061_AMS549BU19/
obj-y += EA8061_AMS549BU19_ID400418/
obj-y += S6E3HA2_AMS509ES01/
#obj-y += S6D7AA0_LSL080AL03_RT8555/
obj-y += TC358764_LTL101AL06_KTD3156/
obj-y += S6D7AA0_LSL080AL03_RT8511/
obj-y += VX5B3D_LTI550HN06/
obj-y += S6D7AA0_LSL080AL03/
obj-y += SC7798A_BV045WVM/
obj-y += HX8369B_BV045WVM/
obj-y += S6D7AA0_LTL101AT01/
obj-y += HX8389C_GH9607501A/
obj-y += S6D78A0_GH9607501A/
obj-y += S6D77A1A01_BV043WVMB1/
obj-y += S6D77A1A01_BV043WVM/
obj-y += S6E3FA3_AMS499ER01/
endif
