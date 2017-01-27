#include<bits/stdc++.h>

using namespace std;

map<char,int> num;

int number(string x){
    int sum=0;
    for(auto i:x){
        sum+=num[i];   
    }
    return sum;
}

int main(){
    num[' ']=num['a']=num['d']=num['g']=num['j']=num['m']=num['p']=num['t']=num['w']=1;
    num['b']=num['e']=num['h']=num['k']=num['n']=num['q']=num['u']=num['x']=2;
    num['c']=num['f']=num['i']=num['l']=num['o']=num['r']=num['v']=num['y']=3;
    num['s']=num['z']=4;
    
    int t;
    cin>>t;
    int TC=1;
    cin.ignore();

    while(t--){
        string x;
        getline(cin,x);
        printf("Case #%d: %d\n",TC++,number(x));        
    }   
    
    return 0;
}
