#include<stdio.h>
#define SIZE 10

int main(){

	int s[SIZE];
	int j;

	for(j=0; j<SIZE; j++){

		s[j]=2*2+j;
	}//end for

	printf("%s%13s\n", "Elements", "Value");

	for(j=0; j<SIZE; j++){
		printf("%7d%13d\n", j, s[j]);
	}//end for


return 0;
}//end main