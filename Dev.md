#include<stdio.h>
int main(){

	//comment
	int n[10]={1,2,3,4,5,6,7,8,9,10};
	int i;

	printf("%s%13s\n", "Element", "Value");

	for(i=0; i<10; i++){
		printf("%7d%13d\n", i, n[i]);
	}//end for

return 0;
}//end main