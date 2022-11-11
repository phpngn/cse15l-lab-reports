# Week 5 Lab Report: Researching Commands

## The Grep Command line option
## 1. Grep -n
The grep -n command will precede each matching line with a line number.

    [cs15lfa22qx@ieng6-201]:skill-demo1:108$ grep -n "The Hijacking of American 77 American 
    Airlines Flight 77" */*/chapter-1.txt
    124:    The Hijacking of American 77 American Airlines Flight 77 was scheduled to depart from Washington Dulles for Los Angeles at 8:10. The aircraft was a Boeing 757 piloted by Captain Charles F. Burlingame and First Officer David Charlebois. There were four flight attendants. On September 11, the flight carried 58 passengers.

In this example, the command grep -n simply finds all lines contain the phrase "The Hijacking of American 77 American Airlines Flight 77" within the text file and displays them along with their line index.

    [cs15lfa22qx@ieng6-201]:skill-demo1:109$ grep -n " American Airlines" */*/chapter-1.txt 
    22:    Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded American Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.
    28:    The security checkpoints through which passengers, including Atta and his colleagues, gained access to the American 11 gate were operated by Globe Security under a contract with American Airlines. In a different terminal, the single checkpoint through which passengers for United 175 passed was controlled by United Airlines, which had contracted with Huntleigh USA to perform the screening.
    38:    Washington Dulles: American 77. Hundreds of miles southwest of Boston, at Dulles 
    International Airport in the Virginia suburbs of Washington, D.C., five more men were preparing to take their early morning flight. At 7:15, a pair of them, Khalid al Mihdhar and Majed Moqed, checked in at the American Airlines ticket counter for Flight 77, bound 
    for Los Angeles. Within the next 20 minutes, they would be followed by Hani Hanjour and 
    two brothers, Nawaf al Hazmi and Salem al Hazmi.
    62:    They were planning to hijack these planes and turn them into large guided missiles, loaded with up to 11,400 gallons of jet fuel. By 8:00 A.M. on the morning of Tuesday, September 11,2001, they had defeated all the security layers that America's civil aviation security system then had in place to prevent a hijacking. The Hijacking of American 
    11 American Airlines Flight 11 provided nonstop service from Boston to Los Angeles. On September 11, Captain John Ogonowski and First Officer Thomas McGuinness piloted the Boeing 767. It carried its full capacity of nine flight attendants. Eighty-one passengers boarded the flight with them (including the five terrorists).22 The plane took off at 7:59. Just before 8:14, it had climbed to 26,000 feet, not quite its initial assigned cruising altitude of 29,000 feet. All communications and flight profile data were normal. About this time the "Fasten Seatbelt" sign would usually have been turned off and the flight attendants would have begun preparing for cabin service.
    74:    About five minutes after the hijacking began, Betty Ong contacted the American Airlines Southeastern Reservations Office in Cary, North Carolina, via an AT&T airphone to report an emergency aboard the flight. This was the first of several occasions on 9/11 
    when flight attendants took action outside the scope of their training, which emphasized that in a hijacking, they were to communicate with the cockpit crew. The emergency call lasted approximately 25 minutes, as Ong calmly and professionally relayed information about events taking place aboard the airplane to authorities on the ground.
    78:    At 8:21, one of the American employees receiving Ong's call in North Carolina, Nydia Gonzalez, alerted the American Airlines operations center in Fort Worth, Texas, reaching Craig Marquis, the manager on duty. Marquis soon realized this was an emergency and instructed the airline's dispatcher responsible for the flight to contact the cockpit. 
    At 8:23, the dispatcher tried unsuccessfully to contact the aircraft. Six minutes later, the air traffic control specialist in American's operations center contacted the FAA's 
    Boston Air Traffic Control Center about the flight. The center was already aware of the 
    problem.
    124:    The Hijacking of American 77 American Airlines Flight 77 was scheduled to depart from Washington Dulles for Los Angeles at 8:10. The aircraft was a Boeing 757 piloted by Captain Charles F. Burlingame and First Officer David Charlebois. There were four flight attendants. On September 11, the flight carried 58 passengers.
    128:    At 8:54, the aircraft deviated from its assigned course, turning south. Two minutes later the transponder was turned off and even primary radar contact with the aircraft was lost. The Indianapolis Air Traffic Control Center repeatedly tried and failed to contact the aircraft. American Airlines dispatchers also tried, without success.
    130:    At 9:00, American Airlines Executive Vice President Gerard Arpey learned that communications had been lost with American 77. This was now the second American aircraft in trouble. He ordered all American Airlines flights in the Northeast that had not taken 
    off to remain on the ground. Shortly before 9:10, suspecting that American 77 had been hijacked, American headquarters concluded that the second aircraft to hit the World Trade Center might have been Flight 77. After learning that United Airlines was missing a plane, American Airlines headquarters extended the ground stop nationwide.
    132:    At 9:12, Renee May called her mother, Nancy May, in Las Vegas. She said her flight was being hijacked by six individuals who had moved them to the rear of the plane. She asked her mother to alert American Airlines. Nancy May and her husband promptly did so.
    144:    At 9:37:46, American Airlines Flight 77 crashed into the Pentagon, traveling at 
    approximately 530 miles per hour.
    158:    United 175 was hijacked between 8:42 and 8:46, and awareness of that hijacking began to spread after 8:51. American 77 was hijacked between 8:51 and 8:54. By 9:00, FAA 
    and airline officials began to comprehend that attackers were going after multiple aircraft. American Airlines' nationwide ground stop between 9:05 and 9:10 was followed by a United Airlines ground stop. FAA controllers at Boston Center, which had tracked the first two hijackings, requested at 9:07 that Herndon Command Center "get messages to airborne aircraft to increase security for the cockpit." There is no evidence that Herndon took such action. Boston Center immediately began speculating about other aircraft that might be in danger, leading them to worry about a transcontinental flight-Delta 1989-that in fact was not hijacked. At 9:19, the FAA's New England regional office called Herndon and asked that Cleveland Center advise Delta 1989 to use extra cockpit security.
    164:    The airlines bore responsibility, too. They were facing an escalating number of 
    conflicting and, for the most part, erroneous reports about other flights, as well as a 
    continuing lack of vital information from the FAA about the hijacked flights. We found no evidence, however, that American Airlines sent any cockpit warnings to its aircraft on 9/11. United's first decisive action to notify its airborne aircraft to take defensive 
    action did not come until 9:19, when a United flight dispatcher, Ed Ballinger, took the 
    initiative to begin transmitting warnings to his 16 transcontinental flights: "Beware any cockpit intrusion- Two a/c [aircraft] hit World Trade Center." One of the flights that received the warning was United 93. Because Ballinger was still responsible for his other flights as well as Flight 175, his warning message was not transmitted to Flight 93 until 9:23.
    270:    The controller checked to see if American Airlines could establish communication with American 11. He became even more concerned as its route changed, moving into another sector's airspace. Controllers immediately began to move aircraft out of its path, and asked other aircraft in the vicinity to look for American 11.
    324:    Manager, New York Center: Okay. This is New York Center. We're watching the airplane. I also had conversation with American Airlines, and they've told us that they believe that one of their stewardesses was stabbed and that there are people in the cockpit 
    that have control of the aircraft, and that's all the information they have right now.  
    388:    American Airlines Flight 77 FAA Awareness. American 77 began deviating from its 
    flight plan at 8:54, with a slight turn toward the south. Two minutes later, it disappeared completely from radar at Indianapolis Center, which was controlling the flight.     
    394:    By 9:20, Indianapolis Center learned that there were other hijacked aircraft, and began to doubt its initial assumption that American 77 had crashed. A discussion of this concern between the manager at Indianapolis and the Command Center in Herndon prompted it to notify some FAA field facilities that American 77 was lost. By 9:21, the Command Center, some FAA field facilities, and American Airlines had started to search for American 77. They feared it had been hijacked. At 9:25, the Command Center advised FAA headquarters of the situation.
    436:    The NEADS technician who took this call from the FAA immediately passed the word to the mission crew commander, who reported to the NEADS battle commander: Mission Crew Commander, NEADS: Okay, uh, American Airlines is still airborne. Eleven, the first guy, he's heading towards Washington. Okay? I think we need to scramble Langley right now. And I'm gonna take the fighters from Otis, try to chase this guy down if I can find him.

Here, the command searches for the matching keyword "American Airline" in a text file and displays all the lines where the keyword appears in along with the line index.

    [cs15lfa22qx@ieng6-201]:skill-demo1:117$ grep -n "human species" */*/*.txt
    technical/plos/journal.pbio.0020101.txt:28:        competitiveness. This is the problem 
    with the human species. Somewhere in all of this
    technical/plos/journal.pbio.0020346.txt:24:        with that of nonhuman species. They conclude that many traits that were formerly thought to

And in this example, the command line searches through multiple files for the keyword "human species" and displays the file where the keyword appear in, the line where the keyword appear in and the line index in that file. 

## 2. Grep -l
The grep -l will list all the matching file where the search phrase appears in. 

Here is an example of the command list all the files that have the keyword "human nature":

    [cs15lfa22qx@ieng6-201]:skill-demo1:128$ grep -l "human nature" */*/*.txt
    technical/plos/journal.pbio.0020101.txt
    technical/plos/journal.pbio.0020140.txt
    technical/plos/pmed.0010052.txt

We can also use the 'ls' and 'grep -l' command together. By using the character '|', we can directs the output of the `ls` command as input for `grep -l "human gene"`.

    [cs15lfa22qx@ieng6-201]:skill-demo1:129$ ls |grep -l "human gene" */*/*.txt
    technical/biomed/1471-2091-3-14.txt
    technical/biomed/1471-2105-2-8.txt
    technical/biomed/1471-2105-3-14.txt
    technical/biomed/1471-2105-3-16.txt
    technical/biomed/1471-2105-3-3.txt
    technical/biomed/1471-2105-3-6.txt
    technical/biomed/1471-2105-4-28.txt
    technical/biomed/1471-2121-2-11.txt
    technical/biomed/1471-2121-4-6.txt
    technical/biomed/1471-2148-2-5.txt
    technical/biomed/1471-2156-2-8.txt
    technical/biomed/1471-2164-2-1.txt
    technical/biomed/1471-2164-2-2.txt
    technical/biomed/1471-2164-2-4.txt
    technical/biomed/1471-2164-2-6.txt
    technical/biomed/1471-2164-2-9.txt
    technical/biomed/1471-2164-3-10.txt
    technical/biomed/1471-2164-3-16.txt
    technical/biomed/1471-2164-3-18.txt
    technical/biomed/1471-2164-3-19.txt
    technical/biomed/1471-2164-3-27.txt
    technical/biomed/1471-2164-4-13.txt
    technical/biomed/1471-2164-4-15.txt
    technical/biomed/1471-2164-4-24.txt
    technical/biomed/1471-2164-4-25.txt
    technical/biomed/1471-2164-4-6.txt
    technical/biomed/1471-2180-1-8.txt
    technical/biomed/1471-2199-2-12.txt
    technical/biomed/1471-2202-4-11.txt
    technical/biomed/1471-2350-3-12.txt
    technical/biomed/1472-6750-1-6.txt
    technical/biomed/1472-6750-2-14.txt
    technical/biomed/1477-7827-1-23.txt
    technical/biomed/1477-7827-1-54.txt
    technical/biomed/bcr317.txt
    technical/biomed/bcr571.txt
    technical/biomed/gb-2000-1-1-research002.txt
    technical/biomed/gb-2001-2-11-research0046.txt
    technical/biomed/gb-2001-2-4-research0011.txt
    technical/biomed/gb-2001-2-4-research0014.txt
    technical/biomed/gb-2001-2-6-research0021.txt
    technical/biomed/gb-2002-3-10-research0055.txt
    technical/biomed/gb-2002-3-5-research0020.txt
    technical/biomed/gb-2002-3-7-research0032.txt
    technical/biomed/gb-2002-3-7-research0036.txt
    technical/biomed/gb-2002-4-1-r1.txt
    technical/biomed/gb-2003-4-1-r7.txt
    technical/biomed/gb-2003-4-4-r28.txt
    technical/biomed/gb-2003-4-5-r30.txt
    technical/biomed/gb-2003-4-6-r37.txt
    technical/biomed/gb-2003-4-7-r46.txt
    technical/plos/journal.pbio.0020206.txt
    technical/plos/journal.pbio.0020241.txt
    technical/plos/journal.pbio.0020276.txt
    technical/plos/pmed.0020212.txt
    technical/plos/pmed.0020235.txt

Finally, we can also use the 'echo' command and grep together. Similar to the previous case, we would also uses the character '|' to directs the output of the `echo ./technical` command as input for `grep -l "Pentagon" */*/chapter-1.txt`. 

    [cs15lfa22qx@ieng6-201]:skill-demo1:136$ echo ./technical |grep -l "Pentagon" */*/chapter-1.txt
    technical/911report/chapter-1.txt

## 3. Grep -v
The Grep -v command will do a invert match, meaning it will search for all the lines that do not contain the search phrase. 

Here is an example of the command gerp -v search for all the lines that do not contain the word "the".

    [cs15lfa22qx@ieng6-201]:skill-demo1:145$ grep -v "the"  */*/chapter-1.txt



    "WE HAVE SOME PLANES"



    INSIDE THE FOUR FLIGHTS


        Boston: American 11 and United 175. Atta and Omari boarded a 6:00 A.M. flight from Portland to Boston's Logan International Airport.




        Between 6:45 and 7:40, Atta and Omari, along with Satam al Suqami, Wail al Shehri, and Waleed al Shehri, checked in and boarded American Airlines Flight 11, bound for Los Angeles. The flight was scheduled to depart at 7:45.


        Their flight was scheduled to depart at 8:00.

















        The 19 men were aboard four transcontinental flights.











































































    IMPROVISING A HOMELAND DEFENSE

    The FAA and NORAD



























    American Airlines Flight 11















        NEADS: Is this real-world or exercise?

        FAA: No, this is not an exercise, not a test.






    United Airlines Flight 175


        UAL 175: New York UAL 175 heavy.

        FAA: UAL 175 go ahead.


        FAA: Oh, okay. I'll pass that along over here.




        The New York Center controller and manager were unaware that American 11 had already crashed.










        Terminal: Got him just out of 9,500-9,000 now.

        Center: Do you know who he is?

        Terminal: We're just, we just we don't know who he is. We're just picking him up now.




        New England Region: Yes, I am.


        Unidentified Female Voice: They have what?

        Boston Center: Planes, as in plural.

























        FAA: Yes.

        NEADS: On its way towards Washington?


        NEADS: Okay.



        NEADS: He-American 11 is a hijack?

        FAA: Yes.

        NEADS: And he's heading into Washington?

        FAA: Yes. This could be a third aircraft.

















        There was no response.


        The controller responded: "United 93, understand you have a bomb on board. Go ahead." The flight did not respond.




        Command Center: Uh, do we want to think, uh, about scrambling aircraft?

        FAA Headquarters: Oh, God, I don't know.






        FAA Headquarters: Yes.










        FAA (DC): Go ahead.

        NEADS: United nine three, have you got information on that yet? FAA: Yeah, he's down.

        NEADS: He's down?

        FAA: Yes.

        NEADS: When did he land? 'Cause we have got confirmation- FAA: He did not land.     

        NEADS: Oh, he's down? Down?















    NATIONAL CRISIS MANAGEMENT










    The Agencies Confer

































        We believe this call would have taken place sometime before 10:10 to 10:15.
















        Controllers: Copy that, sir.

        Floor Leadership: So if you're trying to divert somebody and he won't divert- Controllers: DO [Director of Operations] is saying no.






        SecDef: Yes, I understand. Who did you give that direction to?



        Vice President: Yes, it has.



        SecDef: We can't confirm that. We're told that one aircraft is down but we do not have a pilot report that did it.






    What If?

We can also combine the command `grep -v` with the command `grep -c` to count  the number of line that does not contain the search phrase. 

Here is an example of this combination on a text file to count how many lines do not contain the keyword "the" .

    [cs15lfa22qx@ieng6-201]:skill-demo1:148$ grep -v -c "the"  */*/chapter-1.txt
    418

Finally, we can use the command `grep -v` together with the command `grep -n` to precede each non-matching line with a line number. 

Below is an example for this combination, numbering all the lines that do not contain the keyword "the" in a text file.

    [cs15lfa22qx@ieng6-201]:skill-demo1:192$ grep -v -n "the"  ./technical/plos/pmed.0020061.txt
    1:
    2:
    3:
    4:
    5:
    6:        Epidemics of overt toxicity following widespread environmental contamination from
    10:        toxins are linked with less overt symptoms of toxicity—intellectual impairments, behavioral
    11:        problems, spontaneous abortions, or preterm births [6,7,8,9,10,11,12,13,14,  
    12:        15,16,17,18,19,20,21,22,23,24,25,26,27, 28,29,30,31,32,33,34,35,36,37,38,39,40]. Moreover,
    14:        linked with lead or tobacco are, for a given increment of exposure, greater at lower levels
    15:        than those found at higher levels [10,41,42,43].
    17:        insecticides—chemicals oftentimes specifically designed to be toxic—are largely unknown
    19:        blood and body fluids of pregnant women and children [45].
    20:
    21:
    22:        Children's Vulnerability to Environmental Toxins
    23:        The developing fetus and young child is particularly vulnerable to certain environmental
    26:        processes include cortical functional differentiation, synaptogenesis, myelination, and
    27:        programmed apoptosis [46].
    28:        Children's exposure to environmental toxins is insidious. Environmental toxins covertly
    29:        enter a child's body transplacentally during fetal development or by direct ingestion of
    32:        chemicals in human tissues and body fluids using biologic markers (biomarkers) enables
    33:        scientists to more effectively link exposures to environmental toxins with disability or
    34:        disease [57].
    36:        developmental neurotoxicity (DNT) and reproductive toxicity is rarely done. DNT testing
    39:        during pregnancy and lactation. Paradoxically, DNT testing of a chemical is seldom
    41:        neurotoxic.
    42:
    43:
    44:        The Prevalence of Diseases and Disabilities Linked to Environmental Toxins   
    45:        Based on parental reports, one in six United States children has one or more 
    46:        developmental disabilities, from a subtle learning disability to overt behavioral or
    47:        emotional disorders [58]. Exposures to environmental toxins have been linked 
    with higher
    48:        rates of mental retardation, intellectual impairment, and behavioral problems, such as
    49:        conduct disorder and attention deficit hyperactivity disorder [16,17,18,     
    50:        19,20,21,22,23,24,25,26,27,30,31,36,37, 38,39,40,41,42,43,59,60,61].
    51:        One in ten US babies is born preterm and about 5% have low birth weight [62,63]. Preterm
    52:        birth, defined as birth at less than 37 weeks of gestation, is a major determinant of
    53:        infant mortality and morbidity throughout childhood [62,63,64]. Exposures to 
    environmental
    54:        toxins such as lead, tobacco smoke, and DDT have been linked with an increased risk for
    55:        spontaneous abortion, low birth weight, or preterm birth [6,9,10,13,14,15,28,32,65,66]. The
    57:        treatment for attention deficit hyperactivity disorder and depression in children
    58:        [62,63,67,68,69,70].
    59:        Multiple risk factors, including both genetic and environmental influences, interact in
    60:        complex and often unknown ways to cause disease and disability in children. But efforts can
    61:        be undertaken to prevent or reduce environmental exposures linked to disease 
    without full
    63:        identify pesticides and industrial chemicals that could cause reproductive or65:        pregnant women and children.
    66:
    67:
    68:        Origin and Evolution of DNT Tests
    69:        The process for testing potential developmental neurotoxins in laboratory animals
    84:
    85:          Children's exposure to environmental toxins is insidious
    86:
    88:        neurobehavioral teratogens for both humans and animals (lead, PCBs, methyl mercury,
    89:        cocaine, alcohol, phenytoin, heroin, methadone, and ionizing radiation) and developed rules
    91:        Test Guidelines (OPPTS 870.6300) had been established for use when submitting chemical data
    94:        specifically designed to be toxic [44].
    95:
    96:
    97:        The Precarious US Framework for Protecting Children
    99:        framework to protect children from environmental toxins is precarious. Under 
    current
    100:        regulations, manufacturers of commercial chemicals (excluding pesticides) are not required
    102:        obligated to supply basic premarket toxicity and exposure data necessary to 
    ensure that
    103:        children will be protected from exposure and potential harm from use of those pesticides.
    106:        chemicals—chemicals for which annual production exceeds 1 million pounds per year
    110:        (http://www.epa.gov/chemrtk/volchall.htm), but this is voluntary.
    112:        are most stringent—regulations require only that DNT testing be evaluated for substances
    114:        conducted only in adult animals. The EPA acknowledges that over 140 registered pesticides
    115:        are neurotoxic (i.e., specifically designed to act against pests by interfering with
    117:        received DNT testing using validated protocols for only nine pesticides [49,75,76,77].
    121:        testing. The assumption underlying this system is that positive findings on 
    earlier, more
    123:        extensive testing by manufacturers, including tests in immature animals. Unfortunately,
    124:        this tiered process has failed to result in appropriate DNT testing. In 1998, an internal
    129:        market.
    130:
    131:
    132:        The European Framework: “REACH”
    136:        assess risks and to introduce measures to reduce those risks [78]. Indeed, chemical
    137:        manufacturers are not required to “prove” that a chemical is safe before marketing it. The
    138:        European Commission proposed a new regulatory framework for chemicals, REACH (Registration,
    139:        Evaluation, and Authorization of Chemicals) [78,79] (Figure 1).
    140:        Under REACH, chemical manufacturers would have to assume a much greater burden for
    142:        European and non-European manufacturers doing business in Europe to submit more extensive
    144:        for those chemicals produced in highest quantity. Chemicals found to be hazardous would be
    146:        are no safer alternatives. This registration process would not guarantee that chemicals are
    149:        regulation is burdensome, costly, and impractical”
    150:        (http://www.accnewsmedia.com/site/page.asp?TRACKID=&VID=1&CID=359&DID=1256).152:        thalidomide epidemic ushered in requirements for pharmaceutical agents to undergo extensive
    153:        premarket testing in clinical trials [80].
    154:
    155:
    156:        Limitations of Existing Animal Tests for DNT
    158:        low-level exposure to environmental toxins can be harmful. The EPA continues to rely
    159:        heavily on data from animal (toxicity) testing conducted on only a single animal species
    161:        screening test typically examine only crude toxicological endpoints such as 
    death, body
    164:        miss important effects such as mood changes, impulsive behaviors, and attentional problems
    165:        that in humans have been shown to result from exposures to environmental toxins
    168:        under current EPA guidelines will detect subtle deficits in key human skills such as
    169:        reading.
    175:        rabbits, but not rats; functional effects have only recently been described 
    [81].
    178:        basis of rodent studies have not been sufficiently protective of human health compared with
    180:        of widespread contaminants such as lead, tobacco, and PCBs that human studies are essential
    181:        to ensure that children are not harmed by low levels of exposure
    182:        [11,12,13,14,15,16,17,18,19,20,21,22, 23,24,25,26,27,28,29,30,31,32,33,34,35,
    183:        36,37,38,39,40].
    185:        standard” for detecting subtle effects of environmental toxins on humans. But
    186:        epidemiological studies are expensive to mount, difficult to execute, and take years to
    189:        painfully slow process. There is also a financial disincentive for chemical 
    registrants to
    190:        voluntarily fund such studies because a positive epidemiological study could lead to
    191:        stricter regulations. More importantly, if society continues to rely on epidemiologic
    193:        will first be harmed.
    194:
    195:
    196:        Steps to Protect Children from Environmental Toxins
    197:        Children must be better protected from both new and existing chemicals that 
    are known or
    198:        possible toxins [49]. To protect children from existing toxins, such as lead, mercury, and
    200:        emissions and exposures. Under our current system, efforts to enhance regulations to
    201:        protect children from confirmed toxins are costly and protracted. Indeed, countless
    203:        is any lesson from our experience with environmental toxins, it is that we need to identify
    206:        are marketed. For all new chemicals, including pesticides, extensive premarket testing
    207:        should be required in multiple animal species of both sexes and at different developmental
    208:        stages. These tests should be designed to have adequate statistical power to detect subtle
    211:        while providing a powerful incentive for industry to develop less toxic chemicals.
    212:        Toxicity testing in animals is essential but insufficient to protect pregnant women and
    214:        persist even after toxicity testing in animals is successfully completed. One additional
    216:        which children could be exposed should undergo more extensive testing in human trials
    219:        is used as intended. For example, once animal toxicity testing of a residential pesticide
    220:        is complete (including DNT and reproductive toxicity testing), a pesticide could undergo
    222:        researchers would compare levels of pesticides found in settled dust, on children's hands,
    227:        purpose, potential benefits, and risks of participating. The trials should be conducted by
    229:        chemical industry—and funded by an industry fee or tax. Community representatives would
    232:        boards. Many families would undoubtedly find it objectionable and would choose not to
    237:        existing approach of disseminating a potential toxin into children's environments without
    240:        are experiments exposing millions of pregnant women and children to potential toxins. Thus,
    243:        continue to disseminate chemicals of unknown toxicity into children's environments or to
    244:        allow children to continually be exposed to prevalent toxins, like lead, despite
    247:        and advocate efforts to reduce children's exposure.
    248:
    249:
    250:        Conclusion
    252:        conduct more tests or analyses to demonstrate that high-production chemicals will not cause
    254:        Chemistry Council—that such regulations would harm industry [83,84]. It is time to
    256:        inadequate to safeguard pregnant women and children. Until a formal regulatory system is
    257:        developed to effectively screen and identify new and existing chemicals that are toxic to
    260:        [85].
    261:
    262:
    263: