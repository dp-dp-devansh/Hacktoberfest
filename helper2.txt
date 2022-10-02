#include <bits/stdc++.h>
#define int long long int
using namespace std;
int MOD = 1e9 + 7;

int mpow(int base, int exp){base %= MOD;int result = 1;while (exp > 0){if (exp & 1)result = ((int)result * base) % MOD;base = ((int)base * base) % MOD;exp >>= 1;}return result;}

void solver(){
	
}

int32_t main(){
	ios_base::sync_with_stdio(NULL);
	cin.tie(NULL);

	int t = 1;
	//cin>>t;
	while (t--){
		solver();
	}
	return 0;
}
