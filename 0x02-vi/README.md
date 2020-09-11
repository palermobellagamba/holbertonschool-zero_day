a, the free encyclopedia
Jump to navigationJump to search
For other uses, see Vi (disambiguation).

vi
vi editing a Hello World program in C. Tildes signify lines not present in the file.
vi editing a Hello World program in C. Tildes signify lines not present in the file.
Developer(s)	Bill Joy
Initial release	1976; 44 years ago
Repository	
ex-vi.cvs.sourceforge.net/ex-vi/ex-vi/
Edit this at Wikidata
Written in	C
Operating system	Unix-like
Type	Text editor
License	BSD License or CDDL
Website	ex-vi.sourceforge.net/ Edit this on Wikidata
vi (pronounced as distinct letters, /viːaɪ/)[1] is a screen-oriented text editor originally created for the Unix operating system. The portable subset of the behavior of vi and programs based on it, and the ex editor language supported within these programs, is described by (and thus standardized by) the Single Unix Specification and POSIX.[2]

The original code for vi was written by Bill Joy in 1976, as the visual mode for a line editor called ex that Joy had written with Chuck Haley.[3] Bill Joy's ex 1.1 was released as part of the first Berkeley Software Distribution (BSD) Unix release in March 1978. It was not until version 2.0 of ex, released as part of Second BSD in May 1979 that the editor was installed under the name "vi" (which took users straight into ex's visual mode),[4] and the name by which it is known today. Some current implementations of vi can trace their source code ancestry to Bill Joy; others are completely new, largely compatible reimplementations.[citation needed][discuss]

The name "vi" is derived from the shortest unambiguous abbreviation for the ex command visual, which switches the ex line editor to visual mode. The name is pronounced /viːaɪ/ (the English letters v and i).

Note: The cursor moves to bottom of screen whenever a colon (:) is typed. This type of command is completed by hitting the <Return> (or <Enter>) key.
*	:x<Return>	quit vi, writing out modified file to file named in original invocation
 	:wq<Return>	quit vi, writing out modified file to file named in original invocation
 	:q<Return>	quit (or exit) vi
*	:q!<Return>	quit vi even though latest changes have not been saved for this vi ca
