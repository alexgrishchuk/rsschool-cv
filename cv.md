# Aliaksandr Grishchuk
## Contact:
* phone: +375 (29) 220-12-09
* email: alex_grishchuk@tut.by
## About Me:
I'm interested in Computer Science. I desire to learn a new field for myself as web development.
## Skills:
* __Programming Languages:__ C, C++, SQL
* __Web Technologies__: HTML, CSS
* __Version Control System__: Git
## Code examples:
```C
void shellsort(Item a[], int l, int r, bool (*comp) (Item, Item))
{
    int i, h;
    for (h = 1; h <= (r-l)/9; h = 3*h+1) ;
    for ( ; h > 0; h /= 3)
    {
        for (i = l+h; i <= r; i++)
        { 
            int j = i; 
            Item v = a[i]; 
            while ((j >= l+h) && (*comp)(v, a[j-h]))
            {   
                a[j] = a[j-h]; 
                j -= h; 
            }
            a[j] = v; 
        } 
    }
}
```
## Work experience: 
2010-2020 - Software engineer at Brestenergo. Responsibilities: network administration and security, technical support for SCADA systems, software maintenance, user support.
## Education:
Brest State Technical University. Faculty of electronic informational systems. Specialty: computers, systems and networks.
## Foreign Language:
English: Pre-Intermediate.