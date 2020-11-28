# MLGov_ext gaming applications (benchmarks) and Datasets

## 1. Gaming Applications/benchmarks
####  A 45-app training set: 13 real-games + 23 RotCC + 9 Mono micro-benchmarks
####  A 20-app training set: 14 real-games + 6 Mono-benchmarks (Mb)

### 1) Real Games 
(Downloadable from apk repositories and installable, but some applications should be installed directly from Google Play Store). 
####  Training applications  (13) 
 '[Dhoom 3](https://apkpure.com/dhoom-3-jet-speed/com.ninetyninegames.dhoomthreejetspeed)', 
 '[avp_evolution](https://en.apkshub.com/app/com.fde.avpevolution)', 
 '[Godzilla](https://godzilla-smash3.en.uptodown.com/android)', 
 '[Bike Rider](https://bike-racing-moto-rider-stunts.en.uptodown.com/android)', 
 '[3dmark_extream](https://3dmark.en.uptodown.com/android)', 
 '[Modern Combat](https://www.hiapphere.com/app/com.gameloft.android.ANMP.GloftM3HM)', 
 '[D-Day](https://frontline-commando-d-day.en.uptodown.com/android)', 
 '[3dmark_normal](https://apkpure.com/3dmark-the-gamer-s-benchmark/com.futuremark.dmandroid.application)', 
 '[Call of Duty](https://call-of-duty-heroes.en.uptodown.com/android)',
 '[Jet Ski 2013](https://jet-ski-free-game.en.uptodown.com/android)', 
 '[Turbo FAST](https://apkpure.com/turbo-fast/com.pikpok.turbo)',
 '[q3zombie_map4](https://q3-zombie.en.uptodown.com/android/download)', 
 '[Edge of Tomorrow](https://edge-of-tomorrow-game.en.uptodown.com/android)',
               
####  Test applications (14)
'[anomaly2_low](https://apkpure.com/anomaly-2-benchmark/com.elevenbitstudios.anomaly2Benchmark)', 
'[dream bike](https://dream-bike.en.uptodown.com/android)', 
'[Action Bike](https://action-bike.en.uptodown.com/android)', 
'[Deerhunter14](https://deer-hunter-2014.en.uptodown.com/android)', 
'[Citadel](https://epic-citadel.en.uptodown.com/android)', 
'[Herculous](https://hercules-the-official-game.en.uptodown.com/android)', 
'[anormaly2_normal](https://apkpure.com/anomaly-2-benchmark/com.elevenbitstudios.anomaly2Benchmark)', 
'[anomaly2_high](https://apkpure.com/anomaly-2-benchmark/com.elevenbitstudios.anomaly2Benchmark)', 
'[q3zombie_map1](https://q3-zombie.en.uptodown.com/android/download)', 
'[300](https://300-seize-your-glory.en.uptodown.com/android)', 
'[GPU Bench](http://gpubench.apk.black/)', 
'[Real Driving](https://real-driving-3d.en.uptodown.com/android)', 
'[Robocop](https://robocop.en.uptodown.com/android)',  
'[q3zombie_map2](https://q3-zombie.en.uptodown.com/android/download)'

### 2) GPU-microbenchmarks 
RotCC_/Mono_/MbXYZ:  X, Y and Z stand for CPU, GPU and Memory workloads respectively [1][2]; and MbXYZ benchmarks are variations of the Mono micro-benchmarks by adding memory workload (Z), in addition to combinations of CPU and GPU workloads (X and Y) <br />
####  &nbsp;&nbsp;&nbsp;&nbsp; Mono-benchmarks (Mb): microbench2.apk
####  &nbsp;&nbsp;&nbsp;&nbsp; RotCC-benchmarks: microbench3.apk

####  Training benchmarks
RotCC_000, RotCC_340, RotCC_030, RotCC_240, RotCC_040, RotCC_250, RotCC_050, RotCC_010, RotCC_120, RotCC_020, 
RotCC_130, RotCC_330, RotCC_540, RotCC_450, RotCC_210, RotCC_200, RotCC_310, RotCC_520, RotCC_430, RotCC_550, 
RotCC_500, RotCC_510, RotCC_300 (23 RotCC benchmarks) <br />

Mono_000, Mono_200, Mono_300, Mono_330, Mono_430, Mono_400, Mono_500, Mono_420, Mono_530 (9 Mono benchmarks) <br />

####  Test benchmarks    
Mb102, Mb111, Mb112, Mb101, Mb103, Mb113 (6 Mb benchmarks) <br /> 


## 2. Android Mobile Gaming Workloads Datasets
(Using the Real Games and GPU-microbenchmarks, total 92 apps including the training real games and micro-benchmarks) 
####  PDM-r1a3b4.csv (By 9-level CPU frequency configurations) <br />
####  PDM-r2b3a4.csv (By 6-level GPU frequency configurations) <br />
(PDM-RGr1a3b4.csv and PDM-RGr2b3a4.csv: 20 Real Games) <br />

#### References
[1] J-G. Park, C-Y. Hsieh, N. Dutt, and S-S. Lim, "Quality-aware Mobile Graphics Workload Characterization for Energy- 
      efficient DVFS Design", Symposium on Embedded Systems for Real Time Multimedia  (ESTIMEDIA 2014), October 2014. <br />
[2] J-G. Park, C-Y. Hsieh, N. Dutt, S-S. Lim: “Synergistic CPU-GPU Frequency Capping for Energy-efficient Mobile Games”, 
       IEEE Transactions on Embedded Computing Systems (TECS), (SCIE),Volume 17, Issue2, January 2018. <br />
