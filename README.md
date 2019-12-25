# ObjectC_return
轉折敘述的返回

程式設計者可能會發現所有城市中都會出現 return 這個敘述句， return 用於從一程式中傳回，也就是說， return 敘述是程式控制傳回到呼叫它的程式中，傳回時可以設計附帶一個傳回值 return value, 或是 return o; 此一敘述也可以用來提早結束程式的執行。

實作範例

       #import <Foundation/Foundation.h>
       
       int main(int argc, const char * argv[])
       {
       
         for(int i=0; i<10; i++)
         {
           if(i==3)
              return 1;
              NSlog(@"%i", i);
         }
         
         return 0;
       
       }

// output: 0
// output: 1
// output: 2
logout 執行完畢

