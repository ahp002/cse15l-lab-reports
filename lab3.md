# Lab Report 3 (Week 5)
---

``Command: grep``

## 4 Interesting Command-Line Options
**Option 1:**

Example: grep -i

Command:
```
grep -i "Francisco" chapter-1.txt
```

Output:
```
Also at 8:52, a male flight attendant called a United office in San Francisco, reaching Marc Policastro. The flight attendant reported that the flight had been hijacked, both pilots had been killed, a flight attendant had been stabbed, and the hijackers were probably flying the plane. The call lasted about two minutes, after which Policastro and a colleague tried unsuccessfully to contact the flight.
    The Battle for United 93 At 8:42, United Airlines Flight 93 took off from Newark (New Jersey) Liberty International Airport bound for San Francisco. The aircraft was piloted by Captain Jason Dahl and First Officer Leroy Homer, and there were five flight attendants. Thirty-seven passengers, including the hijackers, boarded the plane. Scheduled to depart the gate at 8:00, the Boeing 757's takeoff was delayed because of the airport's typically heavy morning traffic.
```

* Explanation: The command grep -i performs a case-insensitive search where it matches the String "Francisco" and returns all lines that match the String within the given file that we give it. It's useful for finding the lines in the given file that match the String you give in the command.

Example: grep -i

Command:
```
grep -i "public" chapter-12.txt
```

Output:
```
                through the processes of the American republic.
                law enforcement, economic policy, foreign aid, public diplomacy, and homeland
                Goals are good. Yet effective public policies also need concrete objectives.
                general public-can judge whether or not the objectives have been attained.
                In an extraordinary public essay asking how Muslims can "drag ourselves out of
                    extend essential infrastructure and minimum public services to major towns and
                figures find it difficult to publicly defend good relations with the other. Today,
                publicized arrests-very public moves for a government that has preferred to keep
                In June 2004, the Saudi ambassador to the United States called publicly-in the Saudi
                    publicly defend-a relationship about more than oil. It should include a shared
                    in public education.
                public portion of his February 2004 worldwide threat assessment to Congress,
            The general public sees attacks on terrorist finance as a way to "starve the
            Public designation of terrorist financiers and organizations is still part of the
                spending and effort. Publicity and the vigilance of ordinary Americans also make a
                and immigration-was not seen as a national security matter. Public figures voiced
                authorities, and vigilance by transportation authorities and the public.
                attack against public transportation.
                changes we recommend, the American public has vested enormous authority in the U.S.
            At our first public hearing on March 31, 2003, we noted the need for balance as our
            Public safety organizations, chief administrative officers, state emergency
                the provision of public safety mutual aid in the National Capital Region and where
                compatible and adequate communications among public safety organizations at the
                    provides for the expedited and increased assignment of radio spectrum for public
            Preparedness in the private sector and public sector for rescue, restart, and
                    company to its employees and the public for legal purposes. Private-sector
```

* Explanation: The command grep -i performs a case-insensitive search where it matches the String "public" and returns all lines that match the String within the given file that we give it. It's useful for finding the lines in the given file that match the String you give in the command.

* Cited Source: I found the command through ChatGPT, I asked it "what are some interesting command-line options for the grep command?" and it gave me a variety to choose from, their descriptions, and how to use them:
```
grep is a powerful command-line tool for searching text files for specific patterns. Here are some interesting command-line options for grep:

-i: This option tells grep to perform a case-insensitive search. For example, grep -i "hello" myfile.txt will match "Hello", "HELLO", and "hello".

-v: This option tells grep to invert the match, i.e., to display all the lines that do not match the pattern. For example, grep -v "error" myfile.txt will display all the lines that do not contain the word "error".

-r: This option tells grep to perform a recursive search, i.e., to search for the pattern in all files and directories within a given directory. For example, grep -r "hello" /home/user will search for the pattern "hello" in all files in the /home/user directory and its subdirectories.

-n: This option tells grep to display the line numbers of the matching lines. For example, grep -n "error" myfile.txt will display the line numbers of all the lines that contain the word "error".

-c: This option tells grep to display the count of the matching lines. For example, grep -c "error" myfile.txt will display the number of lines that contain the word "error".

-e: This option tells grep to search for multiple patterns. For example, grep -e "error" -e "warning" myfile.txt will search for lines that contain either the word "error" or the word "warning".

-A n: This option tells grep to display n lines after the matching line. For example, grep -A 2 "error" myfile.txt will display the matching line and the next two lines.

-B n: This option tells grep to display n lines before the matching line. For example, grep -B 2 "error" myfile.txt will display the matching line and the previous two lines.

-C n: This option tells grep to display n lines before and after the matching line. For example, grep -C 2 "error" myfile.txt will display the matching line and the previous and next two lines.

These are just a few of the many command-line options available for grep. You can find more options in the grep manual page by typing man grep in the terminal.
```

**Option 2:**

Example: grep -v

Command:
```
grep -v "a" bcr583.txt
```

Output:
```   
        Introduction
      
      
        Methods
        
        
        
          r = 0.25) [ 14 ] .
          reported, were eligible for inclusion in the study ( 
          both 
          not fill out the high school diet section of the 1986
        
        
          t -tests.
          5 versus Q 
          30 or older).
        
      
      
        Results
        5 ] = 0.85, 
        (RR [Q 
        5 ] = 0.78; 
      
      
        Discussion
        estrogen levels; fiber binds estrogen excreted into the
        Second, the 24-item FFQ is too short for complete
        restricted list of foods from which the nutrients were
        
        finding of the present study.
        Hislop 
      
      
        Conclusion
        of diet.
      
      
        Competing interests
```

* Explanation: The command grep -v takes in a txt file and a pattern, it displayed all the lines in the file that didn't match the String "a". This command is useful for displaying the lines that don't match the given pattern in the command.

Example: grep -v

Command:
```
grep -v "o" bcr583.txt
```

Output:
```
 after 1942 were assigned 'enriched' values. The
          adult ( 
          r = 0.25) [ 14 ] .
          n = 1313). The analysis included
          breast cancer. One hundred and thirty-six cases died
          menarche was greater than 21 years ( 
        
        
          Statistical analysis
          t -tests.
          intake (Q 
          5 versus Q 
          in 1980 [ 15 ] . Current vitamin A intake was included in
        
      
      
        Results
        fat (RR [Q 
        5 ] = 0.85, 
        P [trend] = 0.05) and dietary fiber
        (RR [Q 
        5 ] = 0.78; 
      
      
        When specific nutrients were examined, increased
        increase risk (such as C 
        
        cancer.
      
      
      
      
      
      
        relative risk.
```

* Explanation: The command grep -v takes in a txt file and a pattern, it displayed all the lines in the file that didn't match the String "o". This command is useful for displaying the lines that don't match the given pattern in the command.

* Cited Source: I found the command through ChatGPT, I asked it "what are some interesting command-line options for the grep command?" and it gave me a variety to choose from, their descriptions, and how to use them:
```
grep is a powerful command-line tool for searching text files for specific patterns. Here are some interesting command-line options for grep:

-i: This option tells grep to perform a case-insensitive search. For example, grep -i "hello" myfile.txt will match "Hello", "HELLO", and "hello".

-v: This option tells grep to invert the match, i.e., to display all the lines that do not match the pattern. For example, grep -v "error" myfile.txt will display all the lines that do not contain the word "error".

-r: This option tells grep to perform a recursive search, i.e., to search for the pattern in all files and directories within a given directory. For example, grep -r "hello" /home/user will search for the pattern "hello" in all files in the /home/user directory and its subdirectories.

-n: This option tells grep to display the line numbers of the matching lines. For example, grep -n "error" myfile.txt will display the line numbers of all the lines that contain the word "error".

-c: This option tells grep to display the count of the matching lines. For example, grep -c "error" myfile.txt will display the number of lines that contain the word "error".

-e: This option tells grep to search for multiple patterns. For example, grep -e "error" -e "warning" myfile.txt will search for lines that contain either the word "error" or the word "warning".

-A n: This option tells grep to display n lines after the matching line. For example, grep -A 2 "error" myfile.txt will display the matching line and the next two lines.

-B n: This option tells grep to display n lines before the matching line. For example, grep -B 2 "error" myfile.txt will display the matching line and the previous two lines.

-C n: This option tells grep to display n lines before and after the matching line. For example, grep -C 2 "error" myfile.txt will display the matching line and the previous and next two lines.

These are just a few of the many command-line options available for grep. You can find more options in the grep manual page by typing man grep in the terminal.
```

**Option 3:**

Example: grep -e

Command:
```
grep -e "membrane" -e "protein" -e "mom"  rr73.txt
```

Output:
```
Immunoblot analysis of metalloproteinases
        metalloproteinases (TIMPs) [ 28].
        3D = three-dimensional; MMP = matrix metalloproteinase;
            no detectable protein other than type I collagen.
            then incubated in the metalloproteinase buffer (0.06 M
            Immunoblot analysis of metalloproteinases
            Cell (BIO-RAD, Hercules, CA). The proteins were
            transferred to a PVDF transfer membrane (BIO-RAD,
```

* Explanation: The command grep -e takes in a txt file and multiple patterns, it displayed all the lines in the file that matched all the Strings "membrane", "protein", and "mom". This command is useful for displaying the lines that match multiple given patterns in the command.

Example: grep -e
Command:
```
grep -e "day" -e "primary" rr73.txt
```

Output:
```
every 5 days. The areas of floating gels were measured
          days, elastase appeared to partially convert some of the
          gradually decreased. Even at day 21, however, there was
          becoming undetectable by 15 days (Fig. 3). The presence
          of neutrophil elastase for the first 5 days converted
          undetectable by 15 days of culture. Addition of NE for
          the first 5 days resulted in conversion of the 57 kDa
            temperature for 1 hour, then exposed to primary
```

* Explanation: The command grep -e takes in a txt file and multiple patterns, it displayed all the lines in the file that matched both the Strings "day" and "primary". This command is useful for displaying the lines that match multiple given patterns in the command so you can narrow the lines down when trying to find a specific one.

* Cited Source: I found the command through ChatGPT, I asked it "what are some interesting command-line options for the grep command?" and it gave me a variety to choose from, their descriptions, and how to use them:
```
grep is a powerful command-line tool for searching text files for specific patterns. Here are some interesting command-line options for grep:

-i: This option tells grep to perform a case-insensitive search. For example, grep -i "hello" myfile.txt will match "Hello", "HELLO", and "hello".

-v: This option tells grep to invert the match, i.e., to display all the lines that do not match the pattern. For example, grep -v "error" myfile.txt will display all the lines that do not contain the word "error".

-r: This option tells grep to perform a recursive search, i.e., to search for the pattern in all files and directories within a given directory. For example, grep -r "hello" /home/user will search for the pattern "hello" in all files in the /home/user directory and its subdirectories.

-n: This option tells grep to display the line numbers of the matching lines. For example, grep -n "error" myfile.txt will display the line numbers of all the lines that contain the word "error".

-c: This option tells grep to display the count of the matching lines. For example, grep -c "error" myfile.txt will display the number of lines that contain the word "error".

-e: This option tells grep to search for multiple patterns. For example, grep -e "error" -e "warning" myfile.txt will search for lines that contain either the word "error" or the word "warning".

-A n: This option tells grep to display n lines after the matching line. For example, grep -A 2 "error" myfile.txt will display the matching line and the next two lines.

-B n: This option tells grep to display n lines before the matching line. For example, grep -B 2 "error" myfile.txt will display the matching line and the previous two lines.

-C n: This option tells grep to display n lines before and after the matching line. For example, grep -C 2 "error" myfile.txt will display the matching line and the previous and next two lines.

These are just a few of the many command-line options available for grep. You can find more options in the grep manual page by typing man grep in the terminal.
```

**Option 4:**

Example: grep -c

Command:
```
grep -c "primary" rr73.txt
```

Output:
```
1
```

* Explanation: The command grep -c takes in a txt file and a pattern, it displayed the number of lines in the file that matched the String/pattern "primary". This command is useful for finding the number of lines in a file that match the given pattern in the command.

Example: grep -c
Command:
```
grep -c "day" rr73.txt
```

Output:
```
7
```

* Explanation: The command grep -c takes in a txt file and a pattern, it displayed the number of lines in the file that matched the String/pattern "day". This command is useful for finding the number of lines in a file that match the given pattern in the command.

* Cited Source: I found the command through ChatGPT, I asked it "what are some interesting command-line options for the grep command?" and it gave me a variety to choose from, their descriptions, and how to use them:
```
grep is a powerful command-line tool for searching text files for specific patterns. Here are some interesting command-line options for grep:

-i: This option tells grep to perform a case-insensitive search. For example, grep -i "hello" myfile.txt will match "Hello", "HELLO", and "hello".

-v: This option tells grep to invert the match, i.e., to display all the lines that do not match the pattern. For example, grep -v "error" myfile.txt will display all the lines that do not contain the word "error".

-r: This option tells grep to perform a recursive search, i.e., to search for the pattern in all files and directories within a given directory. For example, grep -r "hello" /home/user will search for the pattern "hello" in all files in the /home/user directory and its subdirectories.

-n: This option tells grep to display the line numbers of the matching lines. For example, grep -n "error" myfile.txt will display the line numbers of all the lines that contain the word "error".

-c: This option tells grep to display the count of the matching lines. For example, grep -c "error" myfile.txt will display the number of lines that contain the word "error".

-e: This option tells grep to search for multiple patterns. For example, grep -e "error" -e "warning" myfile.txt will search for lines that contain either the word "error" or the word "warning".

-A n: This option tells grep to display n lines after the matching line. For example, grep -A 2 "error" myfile.txt will display the matching line and the next two lines.

-B n: This option tells grep to display n lines before the matching line. For example, grep -B 2 "error" myfile.txt will display the matching line and the previous two lines.

-C n: This option tells grep to display n lines before and after the matching line. For example, grep -C 2 "error" myfile.txt will display the matching line and the previous and next two lines.

These are just a few of the many command-line options available for grep. You can find more options in the grep manual page by typing man grep in the terminal.
```
