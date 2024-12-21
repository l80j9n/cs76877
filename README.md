java c
Comp 330 (Fall   2024):   Assignment   2
1.    Let   A   be   the   automaton   depicted   below.

(a)    (10 points)    Compute   a   minimal   deterministic ﬁnite   automata   (DFA) from   A.
(b)    (10 points)    Using   the   minimal   DFA   to   determine   a   regular   expression   representing   L(A)
2.    (20 points)    Let   Σ be   a   (non-empty)   alphabet   and   let   w      ∈   Σ*    be   a   string.    We   say   that   x   ∈   Σ*    is   a preﬁx   of   the   string   w   if   there   exists   a   string   u   ∈   Σ*    such   that   w   = xu.
Consider the following language
L = {w   ∈   {a,   b}* |for   every   preﬁxx   of   w   nb   (x)   ≥ na   (x)}
Prove that L is a context-free language.   Your proof should rely on mathematical induction.
3.    (10 points)    Compute   the   Chomsky   Normal   Form   of   the   following   context-free   grammar   (CFG).
S   →   aAa|bBb|∈
A   →   C|a
B   →   C|bC   →   CDE|∈
D   →   A|B|ab
4.    (20 points)    State   whether   the   following   claim   is   true   or   false   and   prove   your   answer.
Claim: For   any   (non-empty)   alphabet   Σ,   there   is   no   language   L ≤ Σ*    which   is   both regular and inherently ambiguous.
Hint:   Use a context-free grammar recognizing L to show a   contradiction if it were   ambiguous.
5.    (20 points)    Build   a   Pushdown   Automaton   (PDA)   recognizing   the   language   L   =   {aibj   |i   =   2   ·   j}.   The   PDA   must   recognize   the   words   by   an empty stack.   Brieﬂy   explain   how   your   PDA   works.   Then,   describe   an   execution   of   your   PDA   on   aaaabb   and   show   it   accepts   it.
6.    (10 points)    Use   the   pumping   lemma   to      show   that   the   language   L      =    {an   bn   an   bn   jn ≥ 0}   is   not context-free.





         
加QQ：99515681  WX：codinghelp  Email: 99515681@qq.com
