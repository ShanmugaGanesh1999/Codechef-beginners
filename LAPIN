#include <stdio.h>

char s[1001];
int i,size,mid,t,yes;
int a[26], b[26];

int main() {
    for (scanf("%d", &t); t--;) {
        scanf("%s", s);
        for (i=0;i<26;i++) {a[i] = 0; b[i] = 0;}
        size = 0;
        while (s[size] != '\0') size++;
        //printf("size = %d\n", size);
        mid = size / 2 - 1;
        //printf("mid = %d\n", mid);
        for (i = 0; i <= mid; i++) a[s[i] - 'a']++;
        if (size & 1) i = mid + 2;
        else i = mid + 1;
        //printf("i = %d\n", i);
        for (; i < size; i++) b[s[i] - 'a']++;
        yes = 1;
        for (i = 0;i<26&&yes;i++) if (a[i] != b[i]) yes = 0;
        yes ? printf("YES\n") : printf("NO\n");
    }
    return 0;
}
