
# 1. Path Hijacking :

In Linux There Is Two Types Of Path : #Absolute_Path and #Relative_Path 

# Absolute Path :

# Key Insights :

1. Every Command in Linux Is A Program.
2. You Should Technically Needed to give a Complete Path From Program To Be Run (which starts with /root.)

Absolute Path Is The Core Of Linux.  The Part Usually Starts With Root. And if You Want to Run Any Program (that should stored in /bin #/bin_means_binaries_here_) Technically You Need to Give That Complete Location Of A Particular Path Which Starts From /root Directory.

# Relative Path :

# Key Insights :

1. Relative Path Is Used For Make User More Efficient For Writing More Useful Programs.
2. It Does Not Complete With A Magic. Even Relative Path Do Look Up For Find A Program.

But, As a User, We Can't Know All Programs #Programs/Path As it Contains Thousand Of Programs That Can Run.

![[Pasted image 20260412095442.png]]

As You Can See Here That There Is 1611 Different Programs That You Can Run  !!

So, You Are Not Going To Remember Or Even Going to Save All Programs With Their Complete Path. SO, the Solution is A Mechanism That Is Working Behind The Scene.

# Let See A Simple Program : ls Program

By Now, You Already Understand That Every Command Is A Program Itself In Linux. Let's Understand "ls" Command. 

# where Program Resides : which Program

Whenever You Want to Look Up For The Residing Location Of Any Program, We Should Use #which Program, That Is Come Preinstalled On Linux.

![[Pasted image 20260412101301.png|637]]

As You Can See Here That 'ls' Command #ls Located On #/bin/ls . Now Whenever You Run #ls Command Ultimately Linux Is Running Only #/bin/ls Command Each And Every Time.

![[Pasted image 20260412101644.png]]

# $PATH Variable :

![[Pasted image 20260412102010.png|637]]

"$PATH" Is A Variable Just Like Other In Programming. That Stores The Searches For Complete Path Of A Program As You Run It, And Stores Lookup Locations For Where To Look For Running Any Linux Program.

# You Can Add Your Own Program And Their Location To Run Instead Of Default Linux Path.


![[Pasted image 20260412105511.png]]


We Have Make Our Program To First Search From #/temp Directory For Any Program. As You Can See, Now #/temp Is First. So Any Command We Will Run It Will Search For #/temp Directory To Be Search For.

# DEMO HACKING SCRIPT

![[Pasted image 20260412104101.png]]

This Is Our #DEMO_HACKING_PROGRAM_ , !!

![[Pasted image 20260412104431.png|627]]

# See This In Action :

![[Pasted image 20260412110904.png|626]]


# You Can Do Same For Other Programs Also :

![[Pasted image 20260412110750.png|622]]

# Result :

![[Pasted image 20260412111537.png]]
