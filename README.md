# pikuniku_tas

welcome to pikuniku_tas! this repo contains all of the most up to date files for tasing this game. pikuniku is tased using libtas, which you can download [here](https://ci.appveyor.com/project/clementgallet/libtas/build/artifacts). please read the sections below for more info:

---

#### navigation

`/ltms` contains updated ltm (libtas movie) files, which store inputs and other data, and can be played back and improved.

within this folder, there are `/category_name` folders for each specific category, and these folders contain the ltms along with a `/wip` folder, which is for unfinished files.

`/lua` contains lua scripts, which can be used in libtas to improve the tools.

within this folder, there is also a `/wip` folder for unfinished scripts.

---

## formatting

please use markers to denote when certain sections of the game start and end. these markers should be named as `level_[start/end (time)]`, where level is the name of the level, and either start is used for the start of a section, or end is used for the end, along with the time the section took to complete. some examples are `menu_start` or `cave_end (46.500)`.

each ltm folder contains an `info.md` file, which is used to give detail about each section of the tas, and uses this format:

```
## marker_name

**route:** (describe the route)

**author(s):** (list of people who worked on the section)
```

the lua folder also contains an `info.md` file, which describes each script and follows this format:

```
## script_name

**function:** (what the script does)

**author(s):** (list of people who worked on the script)
```

---

thanks for reading, and have fun tasing!
