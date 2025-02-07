# insert-element-into-array

int[] a={1,2,34,4,5,6,7};
     int k=4;//value
     int in=3;//index
     for(int i=0;i<a.length;i++)
     {
         if(i==in)
         {
             a[i]=k;
         }
     }
     for(int j=0;j<a.length;j++)
     {
         System.out.println(a[j]);
     }
