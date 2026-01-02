# AS400
RLS AS400
/* Programmer menu started */         
> Call Library
call dg4ibutl/lfinituat

> Check Job             
WRKACTJOB SBS(QUSRWRK) JOB(QZRCSRVS)

> Work Object  
wrkobj LFG151CT

>Call Program
CALL LFG151CT
