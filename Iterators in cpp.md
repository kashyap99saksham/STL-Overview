
# Iterators in CPP
vector < int > v  = {10 ,20,30,40}
vector< int >  :: iterator i = v.begin();
OR 
auto i = v.begin();

## next(i)
next function go to next position of iterator AND RETURN ITERATOR
cout<<<*i<<" ";    //10
i = next(i);
cout<<(*i)<<" ";   //20

> We can pass position in next (how many position)
i = next(i  , 2);   //Go 2 position ahead
 
## prev(i)
prev function go to previous position of iterator AND RETURN ITERATOR
cout<<<*i<<" ";    //20
i = prev(i);
cout<<(*i)<<" ";   //10

> We can pass position in next (how many position)
i = prev(i  , 2);   //Go 2 position back
 
##  advance(i,3)
 It go n position ahead AND MODIFY THE SAME ITERATOR

## Types of Iterators
- INPUT   (only read)
- OUTPUT (only write)
- FORWARD (go forward one step)
- BI-DIRECTIONAL (go forward as well as backward one step)
- RANDOM (go bi-direction and any no. of steps)


		
