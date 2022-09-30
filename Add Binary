class Solution {
public:
    string addBinary(string a, string b) {
     
        int i=a.length()-1,j=b.length()-1;
        int carry=0;
        string sum="";
        while(i>=0|| j>=0 || carry==1)
        {
            carry+=i>=0? a[i]-'0':0;
            carry+=j>=0? b[j]-'0':0;
            
            sum+=char(carry%2+'0');
            carry/=2;
            
            i--;
            j--;
        }
        reverse(sum.begin(),sum.end());
        return sum;
    }
};
