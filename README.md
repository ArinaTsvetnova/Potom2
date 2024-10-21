#inclufe"Library.h"
#incluse"familia.h"
using namespace std;
( if (masiv2[j] != 0) cout << masiv2[j] << endl
)
int main()
(
SetConsoleCP(1251);
SetConsoleOutputCP(1251);

int mass[S] - ( 4, 11, 23, 8, 19 );
cout << arr_sum(mass, 5);
)


#pragma once
void _sort_arr(int* arr, int razmer)
 ( int kor = 0; int temp = 0; for (int i = 0; i < razmer; 1++)
   ( kor = 1; for (int k = 0; k < razmer; k++)
     ( if (arr[kor] < arr[k])
       (
           kor = k;
           temp = arr(i); arr(i) = arr(kor); arr(kor) = temp;
       )
     )
   )
 )  
 
void _dublir_arr(int data[], int _size)
(   int c; const int n = 1000;
    int masiv2[n] = ( 0 ); for (int i = 0; i <= _size - 1; i++)
    (c = data[1]; for (int j = i + 1; j <= _size - 1; j++)
       ( if (data[j] == c) ( masiv2[i] = c; ) )
    )   
)
    for (int i = 0; i <= _size - 1; i++)
    ( for (int j = i + 1; j <= n - 1; j++)
      ( if (masiv2[j] == masiv2[i]) masiv2[i] = 0; )
)
for (int j = 0; j <= n - 1; j++)
