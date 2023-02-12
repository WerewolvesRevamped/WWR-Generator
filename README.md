# WWR-Generator
Data for the WWR role generator

# Format
  
{  
"generator_settings": {  
  "start_power": <Integer>, // the starting value of the role, each ability adds or substracts to it  
  "minimum_power": <Integer>, // the weakest allowed role  
  "maximum_power": <Integer>, // the strongest allowed role  
  "double_name": <Boolean>, // in case only one ability is chosen, is it allowed to use both of the name segments from that ability?  
  "random_abilities": <Boolean> // selects completely random abilities if true, otherwise selects a maximum of one ability from each pool  
},  
    
"win_condition": "0) <Text>\n", // the base win condition  
    
"default": {"noun": "<Noun>", "adjective": "<Adjective>", "power": 0, "basics": "", "details": "", "win": "", "setup": "", "role": ""},  
// the default noun and adjective for the team  
  
"abilities_names": [  
  "<Ability Pool #1 Name>",  
  "<Ability Pool #2 Name>"  
],  
// Names for the ability pools  
  
"abilities": [  
  [  
    {"noun": "<Noun>", "adjective": "<Adjective>", "power": <Power Integer>, "basics": "<Basics Desc>", "details": "<Details Desc>", "win": "<Win Condition Desc>", "setup": "<Setup Commands>", "role": "<Additional Roles>"},  
    {"noun": "", "adjective": "", "power": 0, "basics": "", "details": "", "win": "", "setup": "", "role": ""},  
  ],  
      
  [  
    {"noun": "", "adjective": "", "power": 0, "basics": "", "details": "", "win": "", "setup": "", "role": ""},  
  ]  
  
]  
  
}  
