# Templates in CPP
## templates are two types :

 - **Function** Template
 - **Class** Template
 
### :apple: **Function** Template

    template < typename T>
    T MyMax(T x,T y)
    {
    	return (x > y) ? x : y;
    }
    int main()
    {
    	cout<<MyMax < int > (3,7);
    	cout<<MyMax < char > ('a' , 'g');
    }

### :grapes: Class Template

    Template <typename T>
    struct Pair
    {
	    int a;
	    inht b;
	    Pair(T x,T y)
	    {
		    a = x;
		    b = y;
	    }
	    T getFirst() {return a;}
	    T getSecond() {return b:}
    }; 
    int main()
    {
	    Pair<int>Pi(3,5);
	    cout<<Pi.getFirst();	// 3
	    cout<<Pi.getSecond();	// 5
    }
