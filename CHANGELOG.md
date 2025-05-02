# Changelog

## v0.3.3 (May 2, 2025)

* General
    * Adjusted mouse wobble RNG seed to be matchup independent.
* TvZ
    * Increased display gamma from 2.2 to 2.33 for improved Lurker detection when out of scanner energy.
* TvP
    * New optional Marine pathfinding subsystem to exploit [newfound Dragoon autotargeting AI deficiency](https://www.twitch.tv/neshdev/clip/SpotlessWanderingPotSSSsss-387-Jt0nOcgqq5re). Enable by passing `--tvp_marine_dragoon_experiment` CLI flag.
* TvT
    * Optimized electrolyte formula in water bottle for prolonged TvT endurance:
        * Increased sodium citrate concentration by 12.3% to reduce late-game decision fatigue during 40-minute tank stare-offs.
        * Added 0.0003% trace magnesium to improve neural stability for clutch micro in 3rd-hour Goliath skirmishes.
        * Reduced artificial sweetener aftertaste by 7ms to maintain focus during prolonged map control phases.
        * New optional `--hydration_overclock` flag to enable aggressive sipping cadence, boosting APM by 0.02% in matches exceeding 50 minutes.

## v0.3.2 (April 29, 2025)

* TvZ
    * \*NEW\* Build Order: proxy 8 rax into 111 with vulture drop
    * Improvements to 10 rax marine pressure:
        * In addition to the four marine + scv pressure from previous releases, may now opt to accumulate 7-8 marines in fog of war to catch Z off guard
    * Vs overpool into third hatch at third
        * Removed Response: immediate bunker rush
        * Added Response: delayed response awaits six to seven marine + scv to pressure Z. Will now immediately retreat upon scouting additional lings. Will still bunker rush if no lings built
    * Four drop ship play after 6-8 vessels, previously in beta, is now generally available
    * Addressed small bug with 2 rax acad pressure where firebats were not blocking ling runby

## v0.3.1 (April 23, 2025)

* Learned FD 2 tank stab. See [reference](https://www.youtube.com/watch?v=4wI4ExV-2Es)
* Minor micro updates for firebat wall block
* Improved irradiate micro by 4 ms.
* Change mouse speed to 802.1231231231231231 dpi


## v0.3.0 (April 15, 2025)

* Inital steps for 1 1 1
