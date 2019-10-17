# MulCQA
Constraint-Based Question Answering with Knowledge Graph

# Entity Linking
The entity linking information is here: https://pan.baidu.com/s/1pMfhn31 passward:7wm9

# Example
CompQ-8             who led the mexican calvary in the battle of puebla?       ["ignacio zaragoza"]        ##golden question and answer
[(False)en.battle_of_puebla:battle of puebla(7,9)]===>who led the mexican calvary in the e1 ||| Battle of Puebla ||| base.culturalevent.event.entity_involved ||| Topic[CVT:0()[SbjCONS:0()|CvtCONS:0()|AnsCONS:0()|OpeCONS:0()]===>ANS:3(F:0.5|P:0.333333333333333|R:1) ||| ["second french empire","charles de lorencez","ignacio zaragoza"] ##topic Entity information===>MulCG information===>answer information (you can get the entity linking result based on the topic information, which contains the ID: mention(span) information)
0.5          0 ||| 2.89938387652163                0              0              0.597598373889923         0.614256858825684         0                0.516524732112885         0              0              0.741370141506195         0              0              0.716085135936737         0                0              0              0              0              0              0              0              0              0              0              0              0              0              0                0              0              0              0              0.519257843494415         0.544825196266174         0.969450831413269                0.971042931079865  ##feature vector in this work
