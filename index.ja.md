---
layout: default
title: Semantic Versioning
---

$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0(B
============================

$B%=%U%H%&%'%"4IM}$N@$3&$K$O!"(B
["$B0MB8@-CO9v(B (DLL$BCO9v(B)"](http://ja.wikipedia.org/wiki/DLL%E5%9C%B0%E7%8D%84 "DLL$BCO9v(B - Wikipedia")
$B$H8F$P$l$F$$$k62$m$7$$>l=j$,B8:_$9$k!#(B
$B%7%9%F%`$,Bg$-$/$J$l$P$J$k$[$I!"(B
$B$^$?%=%U%H%&%'%"$K$h$jB?$/$N%Q%C%1!<%8$rE}9g$7$F$$$/$[$I!"(B
$B$"$kF|FMA3$3$N@dK>$N1o$KN)$C$F$$$k$3$H$K5$$,$D$/$3$H$K$J$j$^$9!#(B


$B0MB8$,B?$$%7%9%F%`$G$N?7$7$$%Q%C%1!<%8%P!<%8%g%s$N%j%j!<%9$O!"D>$A$K0-L4$XJQ$o$k$G$7$g$&!#(B
$B0MB8;EMM$r87$7$/$7$?>l9g$O!"%P!<%8%g%s%m%C%/(B
($B$9$Y$F$N0MB8%Q%C%1!<%8Kh$K?7$7$$%P!<%8%g%s$r%j%j!<%9$7$J$1$l$P%Q%C%1!<%8$N%"%C%W%0%l!<%I$,$G$-$J$$(B)
$B$N4m81$,$"$j$^$9!#(B
$B0MB8;EMM$r4K$/$7$?>l9g$O!"I,A3E*$K%P!<%8%g%s$N:.Mp(B
($BE,@Z$J%P!<%8%g%s$G$O$J$/!">-Mh$N%P!<%8%g%s$H8_49@-$^$G2>Dj$7$F$7$^$&(B)
$B$r>7$/$3$H$K$J$j$^$9!#(B
$B%P!<%8%g%s%m%C%/$d%P!<%8%g%s$N:.Mp$K$h$j!"(B
$B%W%m%8%'%/%H$r4JC1$K!"$^$?0BA4$K0\F0$G$-$J$/$J$k$N$,0MB8@-CO9v$G$9!#(B

$B$3$NLdBj$N2r7h$H$7$F!"(B
$B$I$N%P!<%8%g%sHV9f$r3d$jEv$F!"2C;;$9$k$+$r7hDj$9$k$?$a$N4J7i$J%k!<%k%;%C%H$HI,MW>r7o$rDs0F$7$^$9!#(B
$B$3$N;EAH$,F0:n$9$k$?$a$K$O!"%Q%V%j%C%/(B API $B$r@k8@$9$kI,MW$,$"$j$^$9!#(B
$B$3$l$OC1$K%I%-%e%a%s%H$+$b$7$l$^$;$s$7!"<B9T$9$k%3!<%I$=$N$b$N$+$b$7$l$^$;$s!#(B
$B$H$K$b$+$/$K$b!"$3$N(B API $B$OL@3N$G@53N$G$"$k$3$H$,=EMW$G$9!#(B
$B0lC6%Q%V%j%C%/(B API $B$r@k8@$7$?$i!"FCDj$N%P!<%8%g%sHV9f$^$G$N2C;;MzNr$rL@5-$7$^$9!#(B
$B%P!<%8%g%s$N%U%)!<%^%C%H$O(B X.Y.Z ($B%a%8%c!<(B.$B%^%$%J!<(B.$B%Q%C%A(B) $B$r8!F$$7$F$/$@$5$$!#(B
API $B$K1F6A$r5Z$\$5$J$$%P%0%U%#%C%/%9$O%Q%C%A$N%P!<%8%g%s$r2C;;$7!"(B
$B8E$$(B API $B$H8_49@-$r;}$D(B API $B$NDI2C$dJQ99$O%^%$%J!<$N%P!<%8%g%s$r2C;;$7!"(B
$B8eJ}Hs8_49$N(B API $B$NJQ99$O%a%8%c!<$N%P!<%8%g%s$r2C;;$7$^$9!#(B

$B$3$l$r(B "$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0(B" $B%7%9%F%`$H8F$S$^$9!#(B
$B$3$N%9%-!<%`$N2<$G$O!"(B
$B%P!<%8%g%sHV9f$H$=$NJQ2=$O!"(B
$BG[2<$NFCDj%P!<%8%g%s$N%3!<%I$H<!$N%P!<%8%g%s$N%3!<%I4V$N=$@5$r0UL#IU$1$7$^$9!#(B
$B%P!<%8%g%sHV9f$N3d$jEv$F$H$=$N2C;;J}K!$NL@<($OI,?\$G$9!#(B

$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$N;EMM(B (SemVer)
-------------------------------------------

$B%I%-%e%a%s%HFb$N%-!<%o!<%I(B
"MUST", "MUST NOT", "REQUIRED", "SHALL", "SHALL NOT", "SHOULD",
"SHOULD NOT", "RECOMMENDED", "MAY", "OPTIONAL"
$B$O(B [RFC2119](http://www.ietf.org/rfc/rfc2119.txt "RFC2119")
([$BF|K\8lLu(B](http://www.ipa.go.jp/security/rfc/RFC2119JA.html "RFC2119JA"))
$B$K5-:\$5$l$F$kDL$j2r<a$9$k!#(B

1. $B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$rMQ$$$k%=%U%H%&%'%"$O!"%Q%V%j%C%/(B API $B$r@k8@$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$B$3$N(B API $B$O%3!<%I$=$N$b$N$G@k8@$9$k$+!"$b$7$/$O%I%-%e%a%s%HFb$K87L)$K;XDj$9$k!#(B
$B$$$+$J$k>l9g$K$*$$$F$b!"$=$l$O@53N$GJq3gE*$G$"$kI,MW$,$"$k!#(B

1. $BDL>o%P!<%8%g%sHV9f$O(B X.Y.Z $B7A<0$G!"(B X, Y, Z $B$O?tCM$K$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
X $B$O%a%8%c!<%P!<%8%g%s!"(BY $B$O%^%$%J!<%P!<%8%g%s!"(BZ $B$O%Q%C%A%P!<%8%g%s$H$9$k!#(B
$B3FMWAG$O!"?tE*$K2C;;$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$BNc$($P(B: 1.9.0 < 1.10.0 < 1.11.0 $B$J$I!#(B

1. $B%Q%C%A%P!<%8%g%s$KB3$$$FG$0U$NJ8;zNs$rDI2C$9$k$3$H$K$h$j!"FCJL$J%P!<%8%g%sHV9f$rL@5-$7$F$b$h$$(B (MAY)$B!#(B
$B$3$NJ8;zNs$O1QJ8;z$G3+;O$7$J$1$l$P$J$i$:(B (MUST)$B!"1Q?t;z$H2#@~(B (-) $B$G7A@.$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$BFCJL$J%P!<%8%g%sHV9f$O!"4XO"$9$k%P!<%8%g%s$h$j$bM%@h=g0L$,Dc$/$J$k!#(B
$BM%@h=g0L$O(B ASCII $B%3!<%I=g$K%=!<%H$9$kI,MW$,$"$k(B (SHOULD)$B!#(B
$BNc$($P(B:  1.0.0beta1 < 1.0.0beta2 < 1.0.0 $B$J$I!#(B

1. $B0lEY%Q%C%1!<%8$N%P!<%8%g%s$r%j%j!<%9$7$?$i!"$=$N%P!<%8%g%s$NFbMF$O=$@5$7$F$O$J$i$J$$(B (MUST)$B!#(B

1. $B%a%8%c!<%P!<%8%g%s$N%<%m(B (0.y.z) $B$O=i4|3+H/MQ$H$9$k!#(B
$B$9$Y$F$,$$$D$G$bJQ99$5$l$k2DG=@-$,$"$k!#(B
$B%Q%V%j%C%/(B API $B$r0BDj(B (stable) $BHG$HH=CG$5$l$F$O$J$i$J$$!#(B

1. $B%P!<%8%g%s(B 1.0.0 $B$O%Q%V%j%C%/(B API $B$rDj5A$9$k!#(B
$B%P!<%8%g%sHV9f$N2C;;J}K!$O$3$N%Q%V%j%C%/(B API $B$H$=$N99?7J}K!$K0MB8$9$k!#(B

1. $B%Q%C%A%P!<%8%g%s(B Z (x.y.Z | x > 0) $B$O!"8eJ}8_49@-$r;}$D%P%0%U%#%C%/%9$rE,MQ$7$?>l9g$K2C;;$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$B%P%0%U%#%C%/%9$H$OIT@5$JF0:n$r=$@5$9$k$?$a$NFbItJQ99$HDj5A$9$k!#(B

1. $B%^%$%J!<%P!<%8%g%s(B Y (x.Y.z | x > 0) $B$O!"8eJ}8_49@-$rJ]$A$D$D!"?7$?$K%Q%V%j%C%/(B API $B$rDI2C$7$?>l9g$K2C;;$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$B%W%i%$%Y!<%H%3!<%I$K?7$?$J5!G=$,DI2C$7$?$j!"2~=$$9$k>l9g$b%^%$%J!<%P!<%8%g%s$r2C;;$9$k$3$H$b$G$-$k(B (MAY)$B!#(B
$B$^$?%Q%C%A%l%Y%k$NJQ99$r4^$a$F$b$h$$(B (MAY)$B!#(B

1. $B%a%8%c!<%P!<%8%g%s(B X (X.y.z | X > 0) $B$O!"%Q%V%j%C%/(B API $B$K8eJ}8_49@-$,$J$$JQ99$r2C$($?>l9g$K2C;;$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B
$B%^%$%J!<%l%Y%k!"%Q%C%A%l%Y%k$NJQ99$r4^$a$F$b$h$$(B (MAY)$B!#(B

$B%?%0$N;EMM(B (SemVerTag)
----------------------

$B%P!<%8%g%s%3%s%H%m!<%k%7%9%F%`(B (Git, Mercurial, SVN $BEy(B) $B$rMxMQ$9$k>l9g$O!"(B
$B$3$N4XO";EMM$rMxMQ$9$kI,MW$,$"$k(B (SHOULD)$B!#(B
$B$3$N%7%9%F%`$rMxMQ$9$k$3$H$K$h$j!"(B
$B%Q%C%1!<%88!::$N<+F02=!"(B
$B$*$h$S%;%^%s%F%#%C%/%P!<%8%g%K%s%0$NE,MQ$H%j%j!<%9$9$k%P!<%8%g%s$N7hDj$r$9$k!#(B

1. $B%P!<%8%g%s%3%s%H%m!<%k%7%9%F%`$G%j%j!<%9$K%?%0IU$1$9$k:]!"%P!<%8%g%s$N%?%0$O%j%j!<%9$9$k:]$O!"(B
"v3.1.0" $B$N$h$&$K(B "vX.Y.Z" $B7A<0$K$7$J$1$l$P$J$i$J$$(B (MUST)$B!#(B

1. $B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$rF3F~$9$k:G=i$N%?%0$O(B "semver" $B$H$9$kI,MW$,$"$k(B (SHOULD)$B!#(B
$B$3$l$O4{B8$N%W%m%8%'%/%H$KBP$7!"(B
$BG$0U$N;~E@$GE,MQ$7!"(B
$B<+F02=%D!<%k$K$h$jH/8+$5$;$k$?$a$G$"$k!#(B

$B$J$<%;%^%s%F%#%C%/%P!<%8%g%K%s%0$rMxMQ$9$k$N$+(B?
-----------------------------------------------

$B$3$l$O?7$7$$3W?7E*9M$(J}$G$O$"$j$^$;$s!#(B
$B<B:]!"$*$=$i$/$3$l$K6a$$2?$+$r<B;\$7$F$$$k$G$7$g$&!#(B
$BLdBj$O(B "$B$^$H$a(B" ($BI8=`2=(B) $B$,IT==J,$H$$$&$3$H$G$9!#(B
$B%P!<%8%g%sHV9f$O@5<0$J;EMM=q$KDj$a$J$$8B$j!"4pK\E*$K0MB84IM}$KBP$7$F$J$s$NLr$K$bN)$A$^$;$s!#(B
$B>e5-$N9M$(J}$KL>A0$HL@3N$JDj5A$r$9$k$3$H$K$h$j!"%=%U%H%&%'%"$N0U?^$r%f!<%6$KDLCN$9$k$3$H$,4JC1$K$J$j$^$9!#(B
$B0lEY$3$N0U?^$rL@3N$K$9$k$H!":G=*E*$K=@Fp$J(B ($B$7$+$7!"$=$3$^$G=@Fp$G$O$J$$(B) $B0MB8;HMQ$r:n@.$9$k$3$H$,$G$-$^$9!#(B

$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$,$I$N$h$&$K0MB8@-CO9v$+$i3+J|$9$k$+!"4JC1$JNc$r<($7$^$9!#(B
"Firetruck" ($B>CKI<V(B) $B$H$$$&%i%$%V%i%j$,$"$C$?$H$7$^$9!#(B
$B$=$l$,%;%^%s%F%#%C%/%P!<%8%g%K%s%0$KE,MQ$7$?%Q%C%1!<%8(B "Ladder" ($B$O$7$4(B) $B$rI,MW$H$7$^$9!#(B
Firetruck $B$,:n$i$l$?;~E@$G$N(B Ladder $B%Q%C%1!<%8$N%P!<%8%g%s$O(B 3.1.0 $B$G$7$?!#(B
Firetruck $B$O(B 3.1.0 $B$G:G=i$KF3F~$5$l$?$$$/$D$+$N4X?t$rMQ$$$F$$$k$?$a!"(B
Ladder $B$X$N0MB8$KBP$7LdBj$J$/%P!<%8%g%s(B 3.1.0 $B$+$i(B 4.0.0 $B$^$G$r;XDj$9$k$3$H$,$G$-$^$9!#(B
$B8=:_(B Ladder $B$N%P!<%8%g%s(B 3.1.1 $B$H(B 3.2.0 $B$,MxMQ$G$-$k$N$G$"$l$P!"(B
$B%Q%C%1!<%84IM}%7%9%F%`$K$=$l$r%j%j!<%9$G$-!"(B
$B$=$l$,4{B8$N%=%U%H%&%'%"$H8eJ}8_49@-$r;}$C$F$$$k$3$H$rGD0.$9$k$3$H$,$G$-$^$9!#(B

$B?.Mj$G$-$k3+H/<T$P$+$j$G!"(B
$B$9$Y$F$N%Q%C%1!<%8$K$*$1$k4X?t$N%"%C%W%0%l!<%I$rI=5-DL$j$G$"$k$HJ]>Z$7$?$$$G$7$g$&!#(B
$B$7$+$78=<B$N@$3&$OE%=-$$$G$9!#(B
$B$=$l$K$D$$$F$O2?$b8}=P$7$G$-$^$;$s$,!"?.Mj$5$l$k3+H/<T$H$7$F$OCm0U$,I,MW$G$9!#(B
$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$rF3F~$9$k$3$H$K$h$j!"(B
$B0MB8$9$k%Q%C%1!<%8$N?7%P!<%8%g%s$K$h$k(B
$B%Q%C%1!<%8$N%j%j!<%9$H99?7$K$+$+$k;~4V$HLLE]$r>J$/$3$H$,$G$-$^$9!#(B
$B$3$l$,?4CO$h$/J9$3$($k$J$i!"@'Hs%;%^%s%F%#%C%/%P!<%8%g%K%s%0$rMxMQ$7!"(B
$B$=$N86B'$K=>$&$HCG8@$7$F$/$@$5$$!#(B
$B$3$N9M$(J}$r9-$a!"B?$/$N?M$,Mx1W$rF@$k$3$H$,$G$-$k$h$&$K!"(B
README $B%U%!%$%k$K$3$N%&%'%V%5%$%H(B ($BK\2H%Z!<%8(B 'http://semver.org/') $B$X$N%j%s%/$r5-:\$7$F$/$@$5$$!#(B

FAQ
---

### $B$$$D(B 1.0.0 $B$r%j%j!<%9$9$k$Y$-$G$9$+(B?

$B%=%U%H%&%'%"$,%W%m%@%/%H$H$7$FMxMQ$5$l$F$$$P!"$=$l$O$9$G$K(B 1.0.0 $B$G$J$1$l$P$J$i$J$$$G$7$g$&!#(B
$B%f!<%6$,0BDj(B (stable) $B$7$?(B API $B$H$7$FMxMQ$7$F$$$k>l9g$b(B 1.0.0 $B$K$9$k$Y$-$G$9!#(B
$B8eJ}8_49$K$D$$$F?4G[$7$F$$$k>l9g$b!"$*$=$i$/(B 1.0.0 $B$G$"$k$Y$-$G$7$g$&!#(B

### $B$3$l$O9bB.3+H/$H9bB.%5%$%/%k$rK8$2$^$;$s$+(B?

$B%a%8%c!<%P!<%8%g%s(B 0 $B$,9bB.3+H/$N$?$a$K$"$j$^$9!#(B
$BKhF|$N$h$&$K(B API $B$rJQ99$7$F$$$k$N$G$"$l$P!"%P!<%8%g%s(B 0.x.x $B$G$"$k$+!"(B
$B$b$7$/$O<gMW%P!<%8%g%s$+$i%V%i%s%A$r@Z$j!"JLJ*$H$7$F3+H/$7$J$1$l$P$J$j$^$;$s!#(B

### $B%Q%V%j%C%/(B API $B$X$N$[$s$N>.$5$J8eJ}Hs8_49$NJQ99$G$b%a%8%c!<%P!<%8%g%s%"%C%W$,I,MW$H$7$?>l9g!"$9$0(B 42.0.0 $B$^$GE~C#$7$F$7$^$$$^$;$s$+(B?

$B$3$l$O3+H/$HH/E8$K4X$9$k=EMW$J<ALd$G$9!#(B
$BB?$/$N0MB8%3!<%I$,$"$k%=%U%H%&%'%"$KBP$7!"4JC1$KHs8_49$NJQ99$O$7$F$O$$$1$^$;$s!#(B
$B99?7$KMW$9$k%3%9%H$O=EMW$G$9!#(B
$BJQ99$N1F6A$r$h$/8!F$$7!"(B
$B$=$N%3%9%H$H$b$?$i$5$l$kMxE@$rE7Gi$K$+$1!"(B
$B%a%8%c!<%P!<%8%g%s%"%C%W$7$J$1$l$P$J$j$^$;$s!#(B

### $B$9$Y$F$N%Q%V%j%C%/(B API $B$r%I%-%e%a%s%H2=$9$k:n6HNL$OKDBg$G$9(B!

$BB>$N%f!<%6$+$i;HMQ$5$l$k$3$H$rL\E*$H$9$k%=%U%H%&%'%"$rJ8=q2=$9$k$N$O!"%W%m$N3+H/<T$H$7$F$N@UG$$G$9!#(B
$BC/$,$I$N$h$&$K%=%U%H%&%'%"$rMxMQ$9$k$Y$-$+!"(B
$B$^$?$I$N$h$&$K0BA4$K8F$S=P$9$+$OJ#;($G$"$j!"(B
$B$3$N$h$&$J%=%U%H%&%'%"4IM}$NJ#;($5$O!"(B
$B%W%m%8%'%/%H$r8zN(E*$K1?MQ$9$k=EMW$J%]%$%s%H$G$9!#(B
$BD9$$L\$G8+$k$H!"(B
$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$H%Q%V%j%C%/(B API $B$NDj5A$K$h$j1_3j$K1?MQ$7B3$1$k$3$H$,$G$-$^$9!#(B

### $B8eJ}Hs8_49$NJQ99$r%^%$%J!<%P!<%8%g%s$H$7$F%j%j!<%9$7$F$7$^$C$?>l9g$I$&$9$l$PNI$$$G$9$+(B?

$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0$N;EMM$K$"$kDL$j!"(B
$B$9$0$KLdBj$r=$@5$7!"(B
$B8eJ}8_49@-$,$"$k?7$7$$%^%$%J!<%P!<%8%g%s$r%j%j!<%9$7$F$/$@$5$$!#(B
$B$3$N$h$&$J>u67$K$*$$$F$G$b!"%P!<%8%g%s$N%j%j!<%9$r=$@5$9$k$N$O<u$1F~$l$,$?$$$H$$$&$3$H$r3P$($F$*$$$F$/$@$5$$!#(B
$BE,@Z$J>l9g$O!"%f!<%6$,LdBj$N$"$k%P!<%8%g%s$K5$IU$1$k$h$&!"LdBj$N$"$k%P!<%8%g%s$rJ8=q2=$7!"%f!<%6$KDLCN$7$F$/$@$5$$!#(B

### $BFbIt$N0MB84X78$N$_$r99?7$7!"8x3+(B API $B$OJQ99$7$J$$>l9g$O$I$&$7$^$9$+(B?

$B$=$l$,8x3+(B API $B$K1F6A$r5Z$\$5$J$$>l9g$O8eJ}8_49$,$"$k$H8@$($^$9!#(B
$B3+H/<T$,5$$,$D$/$h$&$K!"%Q%C%1!<%8$N0MB84X78$K$=$N%Q%C%1!<%8$,0MB8$7$F$$$k%=%U%H%&%'%"$N0MB8;EMM$bI,MW$G$9!#(B
$BJQ99$,%Q%C%A%l%Y%k$+!"%^%$%J!<%l%Y%k$+$r7hDj$9$k$N$O!"(B
$B%P%0$N=$@5!"$b$7$/$O?7$7$$5!G=$rDI2C$9$k$?$a$KFbIt$N0MB84X78$r99?7$7$?$+$I$&$+<!Bh$G$9!#(B
$BFbIt$N0MB84X78$r99?7$7$?>l9g$O!"%^%$%J!<%l%Y%k$N99?7$H$J$j$^$9!#(B

$B$3$N%I%-%e%a%s%H$K$D$$$F(B
------------------------

$B%;%^%s%F%#%C%/%P!<%8%g%K%s%0;EMM$O(BGravatars $B$NAO@_<T$G$"$j(B GitHub $B$N6&F1AO@_<T$G$"$k(B
[Tom Preston-Werner](http://tom.preston-werner.com) $B$K$h$C$F=q$+$l$F$$$^$9!#(B

$B$b$7!"%U%#!<%I%P%C%/$7$?$$>l9g$O(B [GitHub](https://github.com/mojombo/semver.org/issues "New Issue") $B$K(B issue $B$rEPO?$7$F$/$@$5$$!#(B

$BF|K\8lLu$K4X$9$k%U%#!<%I%P%C%/$O!"$I$&$h$&$K(B [GitHub](https://github.com/Surgo/semver.org.ja-JP/issues/new "New Issue") $B$K(B issue $B$rEPO?$7$F$/$@$5$$!#(B
