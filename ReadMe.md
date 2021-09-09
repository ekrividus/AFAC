# Astral Flow & Astral Conduit automation tool

Will use Apogee > AF > BP > Mana Cede > BP > AC > BPs  
Will Convert when below your MP threshold  
Will attempt to resummon the avatar for your chosen BP should it die mid AFAC  

---

### Usage:
* `afac start|go|on` - Starts the AFAC run, this will not auto-engage your pet if you need it engaged do that first
* `afac stop|end|off` - Stops the AFAC run, if your target dies or w/e, otherwise it'll stop all on its own after AC wears
* `afac bp <Blood Pact Name>` - Sets the BP to use, does not check against your summoned avatar
* `afac mp [number]` - Sets your MP threshold for Converting, defaults to 300 if no number is provided
* `afac skip` - Will not actually use AF AC but will use Apogee/BP/Manacede/BP
* `afac show` - Will show current settings
* `afac debug` - Will print debug information during use
