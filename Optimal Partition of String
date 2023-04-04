class Solution {
public:
    int partitionString(string s) {
        int ar[26] , c=1;
        for(int a: s){
            if(ar[a-'a']==1){
                c++;
                memset(ar,0,sizeof(ar));
            }
            ar[a-'a'] = 1;
        }
        return c;
    }
};
