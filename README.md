
Hi. My name is Thomas. The "guiding spirit" multisearch startpage is my project I recently was creating.


I wanted to create a startpage, which would be universal, customisable and userfriendly.

I'm not good at wording so I want to put things straight.

The startpage offers some mainly used search engines over the web and translators.


Main functions:
Storing queries, autocomplete, bookmarks (left and right side), themes, search by date, by language, by type of content and by selected search engine.
It allows to store default language to the menu (by default EVERYTHING), it allows to delete items from the lists (drag to the right)
it allows to reposition the radiobutton form panel below.
It is fully (I think) rescallable to the window size.
The wallpaper will change with every refresh if you set in the WALLPAPER COUNT how many you need.

The site was tested multiple times on Firefox and also on Opera.

To sort items (drag up/down), to modify and add new.

Safety:
All the data, (autocomplete, lists, values) is stored to local where cookies are.
The site is 100% safe. feel free to upload it to VirusTotal.com and check if you have to, but there might be also falsepositive.



If I broke some rule, I will definitely delete the site or change to be everything right.


Please consider some small help to my dog, Cody. I was doing this project mainly for him because he needs special treatment to cure his cancer, I want to give him as much love and life as I can.
I'm trying to keep him happy. He also has biggest apetite from all dogs after taking the treatment.



Have a good day
- TomekTomkowy





To the developers:

If you want to add new theme, look up here:

an example theme:

['sunny',		'#f0fde2',	'1',	'#e0edd2',		'rgba(255, 255, 240, 0.75)',	'rgba(40, 70, 75, 0.85)',		'rgba(200, 200, 180, 1.0)',	'#214340',		'rgba(220, 225, 200, 0.45)',	'rgba(120, 220, 120, 1.0)'	,'#707070',		'rgba(240, 240, 140, 1.0)',		'rgba(166, 165, 177, 0.36)',	'rgba(66, 65, 77, 0.36)',		'rgba(120, 120, 120, 1.0)',		'rgba(255, 255, 167, 0.53)',	'rgba(240, 230, 150, 0.2)',		'rgba(230, 240, 255, 1.0)',		'rgba(146, 180, 180, 0.43)',	0,3],
//legend:
// 0: THEME NAME, WALLPAPER NAME
// 1: THEME COLOR
// 2: WALLPAPER COUNT (wallpaper name will be ignored if 0. An example: three wallpapers for a theme named "nigtly" would be: "w_nightly_0.jpg", "w_nightly_1.jpg", "w_nightly_2.jpg" the 'w' stands for wallpaper)
// ----------------------
// 3: BACKGROUND COLOR
// 4: MENU AND QUERY EDITBOX BACKGROUND
// 5: MENUITEM ON HOVER
// 6: MENUITEM SELECTION
// 7: TOOLBOX RADIO BUTTONS, LABEL, QUERY NORMAL
// 8: PANEL FORM LEFT SIDE BACKGROUND
// 9: BUTTONS AND QUERY INPUT BORDERS ON FOCUS
// 10: BUTTONS AND QUERY INPUT BORDERS NORMAL
// 11: TOOLBOX SELECTED LABEL, MENU SELECTED LABEL
// 12: TOOLBOX RADIO BUTTONS FORM BACKGROUND
// 13: AUTOCOMPLETE FORM BACKGROUND
// 14: TOOLBOX RADIO BUTTONS SELECTION SHADOW
// 15: BUTTONS AND QUERY INPUT SHADOW ON HOVER
// 16: TITLE LABEL COLOR A
// 17: TITLE LABEL COLOR B
// 18: TOOLBOX FORM BACKGROUND
// 19: WALLPAPER MOSAIC BOOLEAN (if you want tiles or big wallpaper)
// 20: WALLPAPER BLUR LEVEL (0-3)


an example search engine code:
["DuckDuckGo", "https://duckduckgo.com/",  "?PARAMLANG&PARAMDAT&q=", "?iax=images&ia=images&PARAMLANG&PARAMDAT&q=", "?iar=videos&iax=videos&ia=videos&PARAMLANG&PARAMDAT&q=", "?&iaxm=maps&PARAMLANG&PARAMDAT&q=","?iar=news&PARAMLANG&PARAMDAT&q=", "?iax=shopping&ia=shopping&PARAMLANG&PARAMDAT&q=", "", '1',   '7','2'],
PARAMLANG is where language defined parameter goes in the dataBaseLanguages.
PARAMDAT is the same but for data.
structure of the search engine table:

//["NAME",  "ADDRESS", "WEB", "IMG", "VIDEO", "MAPS", "NEWS", "SHOPPING",  'SKIN', 'LANGUAGE PATTERN TYPE', 'DATA PATTERN TYPE'],

they contains templates with parameters used by certain websites.


I may update the project if it will meet with some positive audience. Thank you for using it if you would.

Notice me about bugs in the DeviantArt comments.

