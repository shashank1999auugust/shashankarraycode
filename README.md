# shashankarraycode

int n= sizeof(arr)/sizeof(int)
 int i, j, min, temp;
   for (i = 0; i < n - 1; i++) {
      min = i;
      for (j = i + 1; j < n; j++)
      if (arr[j] < arr[min])
      min = j;
      temp = arr[i];
      arr[i] = arr[min];
      arr[min] = temp;
   }
