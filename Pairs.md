# Pair In STL

   Actually STL library already wrote this type of class for pair etc.
   
    #include <iostream>
	using namespace std;
    template <typename T1, typename T2>
    struct Mypair
    {
        T1 a;
        T2 b;
        Mypair(T1 x,T2 y)	
        {
            a = x;
            b = y;
        }
        T1 first()	{	return a;	} 
        T2 second() {	return b; 	} 
    };
    int main()
    {
	    ***THIS IS OUR PAIR***
        Mypair < char,int > pi('a',4);
        cout<<pi.first()<<" ";		//a
        cout<<pi.second()<<" "; 	//4
        
        ***THIS PAIR IS PROVIDED IN STL***
        pair<char,int> p(5,3);
        cout<<p.first()<<" "<<p.second()<<" ";
        return 0;
    }

   ## Ways to initialize PAIRs
   - pair<int ,int > p(5,6);
   - pair<int ,int> p;
		  p = {5,6};
		 ***or***
		 p = make_pair(5,6);


  