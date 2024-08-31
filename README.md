## RCA

Directly copying the condition object copies the same object instance in both sources.
<br/>
So, for conditions with no initial value, the same instance was copied to both sources; hence, a change in one instance was reflected in the other.
## Solution 
changed it to deep copy using spread operator (here it a simple object so spread operator can be sued for deep copy).
<br/>
For nested object would have used other deep copy methods like `structuredCopy`
