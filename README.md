```
#include <chrisdallat.h>
#include <github.h>
#include <google.h>
#include <vscode.h>

int main() 
{
    char* lang[3][3] = {"C", "JS", "RB"};
    int count = count_lang(lang);
    int i = 0, new_lang_flag = 0, time = 0;
    printf("reach me at: chr15dallat@hotmail.co.uk");
    while(!new_lang_flag)
    {
        for(i = 0, i < count, i++)
            improve_at(lang[i]);
        time++;
        new_lang_flag = check_proficiency(time);
    }
    printf("UPDATE: add new language to lang array");
    return 0;
}
```
