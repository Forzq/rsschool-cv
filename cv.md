## Matvey Shablinskiy
## How can you find me?
### My email: matveyshablinskiy@gmail.com
### Discord: Forz#8442
## About me
### Im 18 years old Belarussian student in Mogilev, want to study as a front-end developer, because at the moment this is an interesting direction for me.
## Professional skills
### I coded on C#, C++, html, css, a little js.
## Example code

``` int q, n, с, e, max_index = 0;
double s = 0, mx;
Console.WriteLine("Введите количество эллементов массива");
n = int.Parse(Console.ReadLine());
Console.WriteLine("Введите число 'c' ");
double c = double.Parse(Console.ReadLine());
Console.WriteLine("Введите массив");
double[] a = new double[n];
for (int i = 0; i < n; i++)
{
a[i] = double.Parse(Console.ReadLine());
if (a[i] > c)
{
s++;
}
}
Console.WriteLine(s + " Кол-во эллементов больше " + c);
mx = a[0];
for (int i = 0; i < n; i++)
{
if (mx < a[i])
{
max_index = i;
mx = a[i];
}
}
double proizv = 1;
if (max_index == n - 1)
{
Console.WriteLine("Максимальный эллемент является последним или единственным в массиве");
}
```
## Experience
### Programming tasks in the University.
### Secondary education at the gymnasium. Now I'm studying in Belarussian-Russian University.
## English level - B1
