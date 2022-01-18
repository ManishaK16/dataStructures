# dataStructures

just check this   https://github.com/codebasics/data-structures-algorithms-python/blob/master/data_structures/2_Arrays/Solution/2_marvel.py
 # leetcode
 container with water # https://www.varsitytutors.com/hotmath/hotmath_help/topics/perimeter-area-volume
Width = horizontal distance between two bars or the difference between their indices.

Length = shorter of the two bars.

Area = (Length * Width)

Area = min(a[1], a[8]) * (8 - 1)
     = min(8, 7) * 7
     = 7 * 7
     = 49
     
 # pointer : no data type (can be typecasted)
 
 void *ptr = &n (& adress)
 
 *(int*)ptr == typecasting a pointer
 
 we cannot deference a void pointer
 
 malloc alloc returns a void pointer so they allocate memory at runtime 
 
 # linked list
 single linked list navigation forward only : data and link == node
 doubly linked list  both ways
 circularly linked list
 
 # merge sort                      
 struct code {    
  int i 
  
  char c
  
  struct code *ptr}   
  
  int main() {
  
  struct code varI
  
  varI.i = 3
  
  VarI.c = 'A'
  
  varI.ptr = null
  we can access a fun in main function like ths
   ------------------------------------------------------------
   import java.util.*;
   
class HelloWorld {

    public static void main(String[] args) {
    
        int n = 4;
        
        int m = 5;
        
        for(int i=1;i<=n;i++){
        
            for(int j=1;j<=m;j++){
            
                if(i==1 || j==1|| i == n || j==m){
                
                System.out.print("*");
                
                }else{
                
                    System.out.print(" "); we need to give space
                    
                
                }
            }
            
            System.out.println();
            
            
        }
        
    }
}
   
  
 
