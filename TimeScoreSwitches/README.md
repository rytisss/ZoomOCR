## Auto time & score switches
### Attack seconds auto-switch to miliseconds 
In some cases attack seconds field can automatically switch when the time left for attack is less than 5 seconds. Luckely this ZoomOCR has function to take it into consideration. Check **'Auto Attack Miliseconds'** flag and this OCR will automatically detect when switch appear. **NOTE!** Put attack seconds (x1) region to cover dot that separates miliseconds from seconds when switch appear. See following pictures for better explanation. When 'switch' will be detected, the software will displayh 'dot detection' (see second picture).  
**Setup**:
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/auto_attack_ms_setup.png" width="1000"/></kbd>  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/auto_attack_ms_point_detectect.png" width="1000"/></kbd>  
**Functionality**:  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/auto_attack_ms_small.gif" width="1000"/></kbd>  
### Minutes to seconds switch  
In some cases minutes switch to seconds when less than one minute is left to play. If auto detection of this transition is desired, activate following flag (**'Auto-Min-To-Sec'**):  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/min_to_sec_small.gif" width="1000"/></kbd>  
### Score position switch 1-10-100 
In some cases score field switches when it transitions from 1 to 10 to 100. To take into consideration, activate following flag (**'Score Field Auto Switch'**):  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/score_digit_switch_small.gif" width="1000"/></kbd>  
### Offset time by 30 minutes in Handball
It if possible to offset time by 30 minutes (add 30 minutes). Activate flag **'+30Min'**:  
<kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/30min_plus_small.gif" width="1000"/></kbd>  
### Time based on history
In some cases, time can be transitioning in funky order when segments turns of not instantly. This cause bad time estimation. This software provide functionality to prevent bad estimation on transition. while taking into consideration prediction history. Check '**Value based on history**':  
| Original (time 'jitter')  | Value based on history |
| ------------- | ------------- |
| <kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/with_transition_small.gif" width="500"/></kbd> | <kbd><img src="https://github.com/rytisss/ZoomOCR/blob/main/res/with_transition_history_small.gif" width="500"/></kbd>   |
