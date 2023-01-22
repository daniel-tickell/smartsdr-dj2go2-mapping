# smartsdr-dj2go2-mapping
How I mapped my keys on my DJ2Go2 Midi device in the Smart SDR Software for flex radio. 

The following details How I mapped out my Midi Device to functions in Smart SDR

![alt text](https://github.com/daniel-tickell/smartsdr-dj2go2-mapping/blob/main/DJ2GO2%20Flex%20layout.jpg?raw=true)

|Button |	Code |	function |
| ------------- |------------- | ------------- |
|Left Slider	  |9|	 Balance Slice A|
|Left Wheel	    |6|	Frequency Slice A|
|Master level	  |3850|	Slice A Volume|
|Left level	    |22|	Mic Gain|
|Left Headphone	|27|	Toggle Mute Slice A|
|Left Sync	    |2|	ATU Tune|
|Left Cue	      |1|	Mode Next Slice A|
|Left Play/Pause|0|	PTT Push Slice A|
|Load 1	        |3842|	Select Slice A
|Load 2	        |3843|	Select Slice B
|Browse (Push)	|3846|	Mute Main Audio
|Right Slider	  |265|	Balance Slice B |
|Right Wheel	  |262|	Frequency Slice B |
|Cue Level	    |3852|	Slice B Volume|
|Right level	  |278|	AGC Threshold|
|Right Headphone|283|	Toggle Mute Slice B|
|Right Sync	    |258|	ATU Tune|
|Right Cue	    |257|	Mode Next Slice B|
|Right Play/Pause|256|	PTT Push Slice B|

The Table below refers to the 1,2,3,4 keys on the left and right, against the mode of the pad, this is cycled using the pad mode button. 

|Mode ->		|Cues	|			  |	Auto	|				 |Manual	|			|Sampler|			|
| ----- |------ | ----------- |------   | -----------    |------    | --------- |------ | --------- |
|Button	|Code	|Function	  |	Code	|Function		 |  Code	|Function	|Code	|Function	|
|Left 1	|1025	|NB Slice A   |	1041	|Open DX Cluster |	1057	|-			|1073	|-			|
|Left 2	|1026	|NR Slice A	  |	1042	|FT8			 |	1058	|-			|1074	|-			|
|Left 3	|1027	|ANF Slice A  |	1043	|Logbook		 |	1059	|-			|1075	|-			|
|Left 4	|1028	|Mode Next Act|	1044	| -				 |	1060	|-			|1076	|-			|
|Right 1|1281	| Open DX Cluster 		  | 1297	| -				 |	1313	|-			|1329	|-			|
|Right 2|1282	| FT8 		  |	1298	| - 			 |	1314	|-			|1330	|-			|
|Right 3|1283	| Logbook 		  |	1299	| - 			 |	1315	|-			|1331	|-			|
|Right 4|1284	| - 	      |	1300	| - 			 |	1316	|-			|1332	|-			|
