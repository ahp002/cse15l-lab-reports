## Lab Report 3 (Week 5)
---

``Command: grep``

# 4 Interesting Command-Line Options
**Option 1:**

Example: grep -i

Command:
```
grep -i "tower" chapter-1.txt
```

Output:
```
Tuesday, September 11, 2001, dawned temperate and nearly cloudless in the eastern United States. Millions of men and women readied themselves for work. Some made their way to the Twin Towers, the signature structures of the World Trade Center complex in New York City. Others went to Arlington, Virginia, to the Pentagon. Across the Potomac River, the United States Congress was back in session. At the other end of Pennsylvania Avenue, people began to line up for a White House tour. In Sarasota, Florida, President George W. Bush went for an early morning run.
    At 8:46:40, American 11 crashed into the North Tower of the World Trade Center in New York City.
    All on board, along with an unknown number of people in the tower, were killed instantly.
    At 9:03:11, United Airlines Flight 175 struck the South Tower of the World Trade Center.
    All on board, along with an unknown number of people in the tower, were killed instantly.
    F-15 fighters were scrambled at 8:46 from Otis Air Force Base. But NEADS did not know where to send the alert fighter aircraft, and the officer directing the fighters pressed for more information:"I don't know where I'm scrambling these guys to. I need a direction, a destination." Because the hijackers had turned off the plane's transponder, NEADS personnel spent the next minutes searching their radar scopes for the primary radar return. American 11 struck the NorthTower at 8:46. Shortly after 8:50, while NEADS personnel were still trying to locate the flight, word reached them that a plane had hit the World Trade Center. 
    In summary, NEADS received notice of the hijacking nine minutes before it struck the North Tower. That nine minutes' notice before impact was the most the military would receive of any of the four hijackings. 
    The controllers observed the plane in a rapid descent; the radar data terminated over Lower Manhattan. At 9:03, United 175 crashed into the South Tower.
Military Notification and Response. The first indication that the NORAD air defenders had of the second hijacked aircraft, United 175, came in a phone call from New York Center to NEADS at 9:03. The notice came at about the time the plane was hitting the South Tower.
    Reagan National controllers then vectored an unarmed National Guard C- 130H cargo aircraft, which had just taken off en route to Minnesota, to identify and follow the suspicious aircraft. The C-130H pilot spotted it, identified it as a Boeing 757, attempted to follow its path, and at 9:38, seconds after impact, reported to the control tower:"looks like that aircraft crashed into the Pentagon sir."
    FAA: That was another-it was evidently another aircraft that hit the tower. That's the latest report we have.
    At the White House, Vice President Dick Cheney had just sat down for a meeting when his assistant told him to turn on his television because a plane had struck the NorthTower of the World Trade Center. The Vice President was wondering "how the hell could a plane hit the World Trade Center" when he saw the second aircraft strike the South Tower.
    The President and the Vice President The President was seated in a classroom when, at 9:05, Andrew Card whispered to him: "A second plane hit the second tower. America is under attack." The President told us his instinct was to project calm, not to have the country see an excited reaction at a moment of crisis. The press was standing behind the children; he saw their phones and pagers start to ring. The President felt he should project strength and calm until he could better understand what was happening.
    At 9:33, the tower supervisor at Reagan National Airport picked up a hotline to the Secret Service and told the Service's operations center that "an aircraft [is] coming at you and not talking with us." This was the first specific report to the Secret Service of a direct threat to the White House. No move was made to evacuate the Vice President at this time. As the officer who took the call explained, "[I was] about to push the alert button when the tower advised that the aircraft was turning south and approaching Reagan National Airport."
```

Explanation: The command grep -i performs a case-insensitive search where it matches the String "tower" and returns all lines that match the String. It's useful for finding the lines that match the String you give in the command.

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

Explanation: The command grep -i performs a case-insensitive search where it matches the String "public" and returns all lines that match the String. It's useful for finding the lines that match the String you give in the command.

**Option 2:**

Example: grep -v

Command:
```

```

Output:
```

```


Example: grep -v

Command:
```

```

Output:
```

```


**Option 3:**

Example: grep -e

Command:
```

```

Output:
```

```


Example: grep -e
Command:
```

```

Output:
```

```


**Option 4:**

Example: grep -c

Command:
```

```

Output:
```

```


Example: grep -c
Command:
```

```

Output:
```

```

