# CBT059
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)
This is still a work in progress. GitHub repos will be deleted and created during this period...
~~~~~~~~~~~~~~~~

//***FILE 059 IS A COMBINATION OF CLISTS AND ASSEMBLER PROGRAMS     *   FILE 059
//*           TO DISPLAY LAST IPL INFORMATION AND TODAY'S DATE      *   FILE 059
//*           ON A HANDY ISPF PANEL.  THIS FILE IS FROM KEN TOMIAK  *   FILE 059
//*           OF THE DEPT OF INFORMATION TECHNOLOGY AND TELECOMMU-  *   FILE 059
//*           NICATIONS (DOITT) OF NEW YORK CITY.                   *   FILE 059
//*                                                                 *   FILE 059
//*           THERE IS A SMALL ADDITION FROM SAM GOLOB.  THIS IS    *   FILE 059
//*           A PANEL CALLED "IDPANEL" WITH A REXX EXEC CALLED      *   FILE 059
//*           "SMCASID".  THIS PANEL IS MEANT TO BE EXECUTED VIA    *   FILE 059
//*           AN ENTRY IN YOUR ISPF COMMAND TABLE ISPCMDS.  THIS    *   FILE 059
//*           PANEL SHOWS USEFUL INFORMATION ABOUT YOUR CURRENT     *   FILE 059
//*           ISPF SESSION THAT IS INVOKING IT.  THE REXX EXEC      *   FILE 059
//*           "SMCASID" OBTAINS YOUR SYSTEM ID AND PUTS IT INTO     *   FILE 059
//*           AN ISPF VARIABLE IN THE SHARED POOL.  THIS IS GOOD    *   FILE 059
//*           IF YOU HAVE MULTIPLE SYSTEMS LIKE WE HAVE.  IF YOU    *   FILE 059
//*           HAVE ONLY ONE SYSTEM, YOU CAN CHANGE IDPANEL TO       *   FILE 059
//*           DELETE THE REFERENCES TO &SYSID AND THE COMMAND       *   FILE 059
//*           SMCASID WHICH OBTAINS IT.  THEN YOU DON'T NEED THE    *   FILE 059
//*           REXX EXEC.  IF YOU HAVE TSO/E 1.4 OR BELOW (WITHOUT   *   FILE 059
//*           REXX) YOU HAVE TO DO THIS ANYWAY, OR USE AN           *   FILE 059
//*           ASSEMBLER PROGRAM TO GET THE SYSTEM ID INTO A         *   FILE 059
//*           VARIABLE INSTEAD.                                     *   FILE 059
//*                                                                 *   FILE 059
~~~~~~~~~~~~~~~~
