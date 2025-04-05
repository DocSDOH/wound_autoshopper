# wound_autoshopper
claude base code build out based off field survival guide for wound time. incorporating a public webpage and eventually gps capabilities with shopping price comparison capacity

the idea is that you have a list of supplies which you need to aquire. this includes typical wound care supplies available at most big box retailers, pharmacies, grocery stores. when it should do a total cart price comparison for that which is needed.

#inventory builder
based off the field guide for wound care. built out by drop down menus for each type of wound or the flow sheet.

#location specific advice
option to do retailer check within walking distance of your gps location- based off phone or other device- or option to enter general area. should be walking distance first, option to choose driving distance allowable.

#shopping cart
Cart structure is based off the wound category and supplies list is pulled from each item needed. this would include cleaning product, prep, primary and secondary dressing. the user can then delete the items which they already have. volume support option would be incorporated into this. 

should categorize each shopping cart item into the category or function it will provide: ie, you need to pick up diapers because they dont have abdominal pads. the shopping cart should categorize this as under absorbant dressing. since its an alternative than the first recommended it would state in grey or smaller text that it is an alternative choice/supplemented choice.

**#future iteration support tools**

volume support
general estimate of volume of supplies needed based off frequency of wound dressing changes after the shopping list has been built.

Cart assistant
goal: eliminate the issue of having to read through a long list of journal entries in order to proceed to the next step. avoid the burden that is present when journaling the previous days activities on an app like whoop.
features: opt in for check out, auditory option with easy button selection on screen. if requirements for each prompt are not met, it will ask directly before proceeding to the next steps. for example: question asked is how many times did you change your dressing and what did it look like on the soiled dressing? if it only recieves an answer for number of times the dressing was changed, it will ask again about the color and characteristics of the discharge. may incorporate additoinal or alternative phrasing such as: "was the soiled dressing any different than yesterday? did it smell or have an odd color?"

stellar features: 
  incorporate healthtech monitoring, so if you moved alot or more than usual it would ask if you dislodged the dressing or had to change it. this could also apply for things like activity detection/exercise detection.
  Weather- if it rained, was hot, high uv index, etc it can ask if the dressing was soiled alot or required changing. if so, how many times.

