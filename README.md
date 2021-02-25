//Radar 
bind "mouse5" "cl_radar_scale 1" and bind "mouse4" "cl_radar_scale 0.5"

//Rate 
cl_cmdrate "128"
cl_updaterate "128"
cl_interp "0"
cl_interp_ratio "1"
rate "128000" 

//Mouse
m_rawinput "1"
m_mouseaccel1 "0"
m_mouseaccel2 "0"
m_mousespeed "0"
sensitivity "1.70"
zoom_sensitivity_ratio_mouse "1.0"

//chat
bind "I" "say_team I'm deaf ears broken - no headphone or microphone. Please share info in team chat in CS:GO, if we want a successful match.

//buy binds
bind "kp_ins" "buy p250"
bind "kp_end" "buy deagle"
bind "kp_downarrow" "buy tec9; buy fiveseven"
bind "kp_pgdn" "buy mp9; buy mac10"
bind "kp_leftarrow" "buy galilar; buy famas"
bind "kp_5" "ak47; buy m4a1"
bind "kp_rightarrow" "buy aug; buy sg553"
bind "kp_home" "buy ssg08"
bind "kp_uparrow" "buy awp"
bind "kp_pgup" "buy hegrenade"
bind "kp_enter" "buy vesthelm"
bind "kp_del" "buy vest"
bind "kp_plus" "buy defuser"
bind "kp_minus" "buy molotov; buy incgrenade"
bind "kp_multiply" "buy flashbang"
bind "kp_slash" "buy smokegrenade"

//smoke+jump
alias "+jumpthrow" "+jump;-attack"; alias "-jumpthrow" "-jump";bind "alt" "+jumpthrow"

//jump+mouse scroll
bind mwheeldown +jump

//viewmodel
viewmodel_fov 60; viewmodel_offset_x 2; viewmodel_offset_y 1.5; viewmodel_offset_z -1; viewmodel_presetpos 0; cl_viewmodel_shift_left_amt 1.5; cl_viewmodel_shift_right_amt 0.75; viewmodel_recoil 0; cl_righthand 1;

//crosshair
cl_crosshairstyle 4;cl_crosshairsize 1.5;cl_crosshairgap -2;cl_crosshairthickness 1;cl_crosshair_drawoutline 0;cl_crosshairdot 0;cl_crosshaircolor 1;cl_crosshairusealpha 1;cl_crosshairalpha 255;cl_crosshairgap_useweaponvalue 0;cl_crosshair_t 0

//cl_bob
cl_bob_lower_amt 5; cl_bobamt_lat 0.1; cl_bobamt_vert 0.1; cl_bobcycle 0.98;

//cleardecals showloadout
bind "W" "+forward; r_cleardecals;cl_showloadout 1"

//game launch 
//-novid -refresh 240 -high +rate 786432 - tickrate 128 +cl_updaterate 128 +fps_max 400 +cl_forcepreload 1 +exec autoexec -language
