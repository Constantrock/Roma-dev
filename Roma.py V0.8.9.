import time
import random
print "LOADING \nStructure...Check\nPersonality...Check\nGladiators...check"
time.sleep(4)
print "SYSTEMS NOMINAL"
time.sleep(2)
wpn = "lol"
print "START"
print """
The year is 173 AD the good emperor Marcus Aurelius rules over Rome
You are a slave, saved from the salt mines of northern Italy
Today seeing that you are strong
A man named marcus lepidus has bought you
"""
print """


Salvete, servi mihi est
(Hello my slaves)
Mihi nomen est Marcus Crassus sed vos domine vocabunt
(My name is Marcus Crassus but you will call me master)
Scriptor nomen tibi scribunt FESTINA
(The scribe will record your name. HURRY)


"""
time.sleep(7)
print "Quid nomen tibi est \n(What is your name?)"
name = raw_input("> ")
print 'You respond with "Mihi nomen est %s" \nwhich is almost all of the latin you know' %name

print "Quid province tibi est\n (What province are you from)"
province = raw_input("> ")
print 'You respond with "%s"' %province
if province == "gaulia":
	print "Nepos mihi habitat ille\n(My grandson lives there)"
else:
	print "Huh, ego habitabam quinque mensies\n(Huh, I lived there for five months)"
time.sleep(3)
print "Et tandem quid genu gladiatores es\n(And finally what knid of gladiator are you)"
time.sleep(2)
print "There are many types of gladiators that can fight in the arena"
time.sleep(2)
print "The three most popular kinds are \nthe murmillo\n the retiarus\n and the samnite"

time.sleep(3)

print "The murmillo has a fish helmet, a sword, and a long shield"

print "The retiarius has a large belt, a trident, and a net"

print "the Samnite has a small rounds shield and a short sword"

time.sleep(2)

print "Which do you decide to be"

GLtype = raw_input("> ")
time.sleep(1)
if GLtype == 'murmillo':
	Gltype = 1
        wpn == "sword"
	print "Murmillo, excellent choice"
elif GLtype == 'retiarius':
	Gltype = 2
        wpn == "Trident"
	print "Retiarius, excellent choice"
elif GLtype == 'samnite':
	Gltype = 3
	wpn == "short sword"
        print "Samnite, excellent choice"
else:
	print "non cognosco, tu samnitum erat\n(I don't understand, you will be a samnite)"
 	Gltype = 3
time.sleep(3)
print """

This game is played through the command line interface
and as such requires two things: reading skills and imagination.

Three choices will be given to you,
stab, block, and bash

Combat is a series of decisions and random occurences which 
can either lead to victory or death.

If you die you can restart the game.

Thank you and enjoy
"""

time.sleep(5)
print "You then march back into line"

print "Let's just skip the training montage"

print "You train very hard every day to become the best"
print "and now you are about to die in a third rate theatre outside pompeii"
time.sleep(2)
print "You see the bright light from the sun coming through curtains"
print "you step outside and see the samnite with his sword"
time.sleep(2)
print 'You stand next to him shoulder to shouder\nand shout "nos morituri te salutamus"\n(we who are about to die salute you)'
print "LET THE GAMES BEGIN"


blckcnt = 0
slscnt = 0
bshcnt = 0
HP = 100
HPE = 100

while True:
	print "HP = %s" %HP
	print "Enemy HP = %s" %HPE
	q = random.randint(1,100)
	print "bash, block, or stab"
	n = raw_input("> ")
	if n.strip() == 'block':
		if q >= 66:
			print "The block was incredibly effective you lose no HP, the samite loses 10"
			HP = HP - 0
			HPE = HPE - 10
		elif q < 66 and q > 33:
			print "The block was mildly effective you lose no HP, the samnite loses none"
		elif q<= 33:
			print "The samnite saw the block from a mile away you lose 20 HP"
			HP - 20
		else:
			print "I have no idea what's wrong"
		blckcnt == blckcnt + 1
	
	
	if n.strip() == 'stab':
		if q >= 66:
			print "The samnite didn't know what hit him and loses 30 HP"
			HPE = HPE - 45
		elif q < 66 and q > 33:
			print "The samnite barely blocks your attack and loses 15 HP"
			HPE = HPE - 25
		elif q <= 33:
			print "The samnite sees the attack coming and loses only 10 HP and you lose 5 HP"
			HP = HP - 5
			HPE = HPE - 10
		else:	
			print "I have no idea what's wrong"
		slscnt = slscnt + 1
	
	if n.strip() == 'bash':
		if q >= 66:
			print "You bash so well that his face nearly caves in he loses 25 HP"
			HPE = HPE - 25
		elif q < 66 and q > 33:
			print "The samnite sees the bash coming and only loses 10 HP"
			HPE = HPE - 10
		elif q <= 33:
			print "You bash so poorly that he stabs you in the gut and you lose 25 HP"
			HP = HP - 25
		else:
			print "I have no idea what's wrong"
		blckcnt = blckcnt + 1
	
	if HP <= 0:
		print "You died at the hands of a samnite in 173 AD outside of pompeii"
		print "only other gladiators came to you funeral"
		print " one of hundreds of thousands of casualties for the sake of entertainment"
		exit()
	if HPE <= 0:
		break
	

time.sleep(2)
print "You stare into his eyes\n ... "
time.sleep(1)
print "you look up to the host of the games"
time.sleep(1)
print "He holds up his hand with his thumb sticking out sideways\n wavering from up to down"
print "He makes his decision"
time.sleep(3)
print "The samnite lives today"
time.sleep(2)
print "Your listor looks impressed"
print "He smiles at you as he hands you your pay for that game"
print "Later a new %s appears at your gear station" %wpn
time.sleep(2)
print "what will you do to prepare for the next battle?"
print "sleep, bathe, or train"
c = raw_input("> ")
if c == "sleep":
     print "you are incredibly uninteresting, but safe"
     print "you awake well rested with 10 more HP"
     HP = 110
elif c == "bathe":
     print "On your way to the bath you notice some slaves"
     print "You ask them how the bath works and they repond"
     print "flamma et ventus roborem adolent"
     print "(fire and wind burn the wood)"
     print "Hic actio aerem sub balneis trans imperium Romae"
     print "(this action heats baths across the roman empire)"

     time.sleep(3)
     print "You thank them and continue with you bathing experience"
     print "you feel more refreshed than ever with 20 more HP"
     HP = 120
elif c == "train":
     print "you injure yourself"
     print "Your friend calls out stultus %s crassus %s" %(name, GLtype)
     print "(stupid %s the stupid %s)" %(name, GLtype)
     time.sleep(2)
     print "You lose 15 HP"
     HP = 85
else:
     print "You mispell something and the NARRORATOR decides you want to train"
     print "you injure yourself"
     print "Your friend calls out stultus %s crassus %s" %(name, GLtype)
     print "(stupid %s the stupid %s)" %(name, GLtype)
     time.sleep(2)
     print "You lose 15 HP"
     HP = 85
time.sleep(2)
print "you look around the ampitheter and realize how huge it is"
print "The gaul in retiarius armor looks bigger"
print 'You look up tho the host and say "nos morituri te salutamus"'
print "You really mean it this time"
print "He yawns"
print "LET THE GAMES BEGIN"
time.sleep(3)
HPE = 250
while True:
	print "HP = %s" %HP
	print "Enemy HP = %s" %HPE
	q = random.randint(1,1000)
	print "bash, block, or stab"
	n = raw_input("> ")
	if n.strip() == 'block':
		if q >= 700:
			print "The block was incredibly effective you lose no HP, the Gaul loses 10"
			HP = HP - 0
			HPE = HPE - 10
		elif q < 500 and q > 333:
			print "The block was mildly effective you lose no HP, the gaul loses none"
                elif q < 700 and q >= 500:
                        print "The block was a catastrophic failure due to the Gaul's strength\n you lose 30 HP"
                        HP = HP - 30
                elif q<= 333:
			print "The samnite saw the block from a mile away you lose 20 HP"
			HP - 20
		else:
			print "I have no idea what's wrong"
		blckcnt == blckcnt + 1
	
	
	if n.strip() == 'stab':
		if q >= 700:
			print "The Gaul didn't know what hit him and loses 30 HP"
			HPE = HPE - 45
		elif q < 500 and q  > 333:
                        print "The Gaul kicks you in the stomach, but you catch his leg\n you lose 10 HP and he loses 20 HP"
                        HPE = HPE -20
                        HP = HP - 10
                elif q < 700 and q >= 500:
			print "The Gaul barely blocks your attack and loses 15 HP"
			HPE = HPE - 25
		elif q <= 333:
			print "The Gaul sees the attack coming and loses only 10 HP and you lose 5 HP"
			HP = HP - 5
			HPE = HPE - 10
		else:	
			print "I have no idea what's wrong"
		slscnt = slscnt + 1
	
	if n.strip() == 'bash':
		if q >= 700:
			print "You bash so well that his face nearly caves in he loses 25 HP"
			HPE = HPE - 20
                elif q < 700 and q >= 500:
                        print "your bash is so ineffetive he laughs and throws you on the ground by your shield"
                        print "You lose 30 HP"
                        HP = HP - 30
                elif q < 500 and q > 333:
                   	print "The Gaul sees the bash coming and only loses 10 HP"
			HPE = HPE - 10
	        elif q <= 333:
			print "You bash so poorly that he stabs you in the gut and you lose 25 HP"
			HP = HP - 25
                else:
			print "You mispelled the command"
                bshcnt = bshcnt + 1
	
	if HP <= 0:
		print "The Gaul proceeds to parade your head around the arena"
		print "You wold think this is embaressing if you were alive"
		print " instead you are one of hundreds of thousands of casualties for the sake of entertainment"
		exit()
	if HPE <= 0:
		break
	

time.sleep(2)
print "With a thud the Gaul falls"
print "The sponsor very decidedly points down"
print "you can barely pick up his head"
print "never the less it is now severed and on your %s" %wpn
time.sleep(4)
print "many years have passed"
print "You have now been called to the arena\neven though you have recieved your rudis, the sign of freedom"
print "do you accept the call from your emperor"
l = raw_input("> ")
if l == "no":
     print "ok"
     print "no glory for you"
     time.sleep(2)
     print "also you are dead"
     exit()
else:
     print "good"

print "you faced seventeen men in the arena\nbefore you recievedyour freedom"
print "and now you will face another"
print "The year is now 183 AD and marcus Aurelius has been dead\n for three years"
time.sleep(3)
print "his son commodus has taken rule over the throne"
print "Commodus has taken a liking to dressing as Hercules and 'fighting'"
print "many have been killed to satiate his fantasy"
print "You may be next"
time.sleep(3)
print "years of training has hardened you, but relaxation made you weak"
print "Let us see who will win"
HP = 350
HPE = 500
time.sleep(1)
while True:
	print "HP = %s" %HP
	print "Enemy HP = %s" %HPE
	q = random.randint(1,1000)
	print "bash, block, or stab"
	n = raw_input("> ")
	if n.strip() == 'block':
		if q >= 750:
			print "The block was incredibly effective you lose no HP, Commodus loses 50"
			HP = HP - 0
			HPE = HPE - 50
		elif q < 750 and q > 650:
			print "The block was mildly effective you lose no HP, the Commodus loses none"
                elif q <= 650 and q >= 450:
                        print "The block was a catastrophic failure due to the sand Commodus kicked\n you lose 30 HP"
                        HP = HP - 30
                elif q < 450 and q >= 200:
			print "The Commodus saw the block from a mile away you lose 20 HP"
			HP - 20
		elif q < 200:
                        print "Commodus drops his sword so you stand there expecting the blow"
                        print "The respite gains you 30 HP"
                        Hp = HP + 30
                else:
			print "I have no idea what's wrong"
		blckcnt == blckcnt + 1
	
	
	if n.strip() == 'stab':
		if q >= 750:
			print "Commodus didn't know what hit him and loses 125 HP"
			HPE = HPE - 75
		elif q < 750 and q  > 650:
                        print "The Commodus kicks you in the stomach with his boot knife, but you catch his leg\n you lose 45 HP and he gains 20 HP"
                        HPE = HPE + 20
                        HP = HP - 45
                elif q < 650 and q >= 450:
			print "Commodus barely blocks your attack and loses 50 HP"
			HPE = HPE - 50
		elif q < 450 and q >= 200:
			print "Commodus sees the attack coming and loses only 20 HP and you lose 15 HP"
			HP = HP - 15
			HPE = HPE - 20
		elif q < 200:
                        print "Commodus' costume gets caught on his sword and you start stabbin"
                        print "Commodus loses 130 HP"
                        HPE = HPE - 130
                else:	
			print "I have no idea what's wrong"
		slscnt = slscnt + 1
	
	if n.strip() == 'bash':
		if q >= 750:
			print "You bash so well that his face nearly caves in he loses 25 HP"
			HPE = HPE - 20
                elif q < 750  and q >= 650:
                        print "your bash is so ineffetive he laughs and throws you on the ground by your shield"
                        print "You lose 30 HP"
                        HP = HP - 30
                elif q < 650 and q > 450:
                   	print "The Gaul sees the bash coming and only loses 10 HP"
			HPE = HPE - 10
	        elif q <= 450 and q >= 200:
			print "You bash so poorly that he stabs you in the gut and you lose 25 HP"
			HP = HP - 25
                elif q < 200:
                        print "Commodus takes a step back and dodges your bash"
                        print "He gains 40 HP from this respite"
                        HPE = HPE + 40
                else:
			print "You mispelled the command"
                bshcnt = bshcnt + 1
	
	if HP <= 0:
		print "Commodus' lust for fame is satiated for now"
		print "Your tombstone is marked 17 wins and one loss"
		print "Your wife cries because of your loss"
                time.sleep(2)
                print "Your friends cry for the lack of honor"
                print "The people cry because this madman is their ruler"
		exit()
	if HPE <= 0:
		break
time.sleep(2)
print "The crowd is in awe of the final blow"
print "The blood splattered sand soaks with bits of emperor"
print "You have finally won"
time.sleep(2)
print "your wife and child run out to you"
print "You celebrate your victory and move to get cleaned"
print "You realize as you hold them that you have killed the emperor"
print "YOU HAVE TO ESCAPE"
time.sleep(2)
print "but that is a story for another day"
print "Good bye %s" %name
