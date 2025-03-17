# kozachnko2
#include <stdio.h>
int main(){
unsigned int num=256;
char *byte=(char*)&num;
if(byte[0]==0 && byte[1]==1){
printf("to je Little Endian");}
else if(byte[0]==1 && byte[1]==0){
printf("to je Big Endian");
}
else
printf("ne viem");

}
