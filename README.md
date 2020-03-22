# GreedyKnapsackproblem
this is a solution to the greedy knapsack problem 












#include<stdio.h>
#include<iostream>
using namespace std:

int main()
{
	int
	cout<<"Enter the number of items"<<endl;
	cin>>n;
	cout<<"enter the time of "<<n<<" items"<<endl;
	for(i=0;i<n;i++)
		cin>>a[i];
	cout<<"Enter the Amount of time we have"<<endl;
	cin>>t;
	for(i=0;i<n;i++)
	{
		for(j=i+1;j<n;j++)
		{
			if(a[i]<a[j])
			{
				t=a[i];
				a[i]=a[j];
				a[j]=t;
			}
		}
	}
	for(i=0;i,n;i++)
		cout<<a[i];
	/*if(n==0 && t==0)
			return 0;
	else
	{	
		usedtime=usedtime+min(a);
		current= t-usedtime;
	}*/

}
