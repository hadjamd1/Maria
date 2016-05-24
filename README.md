# Maria
#		python code
#		script_name:
#
#		author:
#		description:
#

from earsketch import * 

init() 
setTempo(120) 

fitMedia(Y18_KEYS_1, 5, 1, 5)
fitMedia(RD_RNB_KEYSRHODES_6, 1, 5, 30)
fitMedia(RD_RNB_KEYSRHODES_7, 2, 9, 17)
fitMedia(RD_RNB_KEYSRHODES_8, 3, 17, 30)

fitMedia(RD_RNB_WARMBASS_2, 4, 5, 30)
fitMedia(Y07_KICK, 6, 5, 30)
fitMedia(Y07_SNARE, 7, 9, 30)


setEffect(5, DELAY, DELAY_TIME, 1200.0)
setEffect(5, DELAY, DELAY_FEEDBACK, -20.0)

setEffect(2, DISTORTION, DISTO_GAIN, 25.0)
setEffect(2, DISTORTION, MIX, 0.2)

finish() 
