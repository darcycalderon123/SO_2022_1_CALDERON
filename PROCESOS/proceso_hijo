#include <sys/types.h>
#include <unistd.h>
#include <stdio.h>
int main(int argc, char *argv[])
{
 
   pid_t pid;

   if((pid=fork())==0){
       printf("Soy el hijo (%d, hijo de %d)\n", getpid(),
       getppid());
   }
   else{
       printf("Soy el padre (%d, padre de %d)\n", getpid(),getppid());
   }
 
   return 0;
 
}