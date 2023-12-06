# lab1.5
include <cstdlib>
#include <iostream>
char*rus(const char*text);
int main()
{
const int len=500 
char line {len+1};
int count=0,temp=0,i
ifstream fin ("text.txt");
if(!fin)
{
cout<<rus("Файла text не существует!");
getch();
return 1;
}
while(fin.getline(line,len)
{
 temp=0
 int l_line=strlen(line);                          
  if (isalpha(line{0])   
