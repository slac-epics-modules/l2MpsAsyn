TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install) into <top>/db
# databases, templates, substitutions like this
DB += mps.db
DB += mps_bpm.db
DB += mps_blen.db
DB += mps_bcm.db
DB += mps_ai.db
DB += mps_scale_factor.db
DB += mps_soft.db
DB += lc2_analog_sw.db
DB += lc2_bpm_sw.db
DB += lc2_watchdog.db

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_template = <templatename>

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

