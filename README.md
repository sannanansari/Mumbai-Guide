# Mumbai-Guide
This repository is for website Mumbai Guide. It was created during hackathon.
In today's it difficult to take local guide(becoz of costing, safety,etc). 
So me and my created this website to eliminate local guide. The website is simple and efficent.

This Repository contain Two folder:-

1. HTML FOLDER CONTAIN ALL THE HTML FILES OF WEBSITES.
2. CSS FOLDER CONTAINS ALL THE CSS FILES OF HTML AND WEBSITE(SOMETIME A SINGLE CSS FILES USE BY ALL).

NOTE:-IF YOU RUN THIS FILE YOU GET ERROR ON IMAGE FILES. BECAUSE WE USE IMAGE DIRECTLY AND DOESNOT HAVE LINK OF IMAGES THAT WHY YOU WILL GET         ERROR ON IMAGES.

Created by: Sanan Ansari , Shaikh Sohail , Rehan Shaikh.


Selection Sort

#A.Introduction:
The Selection Sort algorithm Sorts an array buy repeatedly finding the minimum element(for ascending Order) from the unsorted part and putting it at beginning.
It is Divided into Two subarray:-
1. The arrauy Which is already Sorted.
2. Which to be Sort(unsorted).


#B.Algorithm:
Step 1 − Set MIN to location 0
Step 2 − Search the minimum element in the list
Step 3 − Swap with value at location MIN
Step 4 − Increment MIN to point to next element
Step 5 − Repeat until xp[la] is sorted

void selection(arr[],n)
  for i=0 to n-1  //one by one unsorted array
    //Finding Minimum Element
 	min = i    //assigning Current as minimum
	for j = i+1 to n
		if arr[j]<arr[min]
			min = j
		end if
	end for	
	//Swaping Current element with minimum element
	swap(arr[min],arr[i])
  end for	

#C.Explanation:-
Selection Sort can be explain on 2 steps:-
1.Find minimum element in unsorted part:- 
		1.Fix min(minimum) as current element.
		2.Then compare min with with unsorted elements.
				a.if any element at that position is greater than current then do nothing.
				b.if any element at that position is smaller than current then fix it as min.  
2.Swap current element arrp[i] with arr[min]:-
		1.It will swap if min is found or Not.
![Example](https://www.google.co.in/url?sa=i&rct=j&q=&esrc=s&source=images&cd=&cad=rja&uact=8&ved=2ahUKEwjGiJrbt5HcAhXXWisKHQg1DhYQjRx6BAgBEAU&url=https%3A%2F%2Fwww.hackerearth.com%2Fpractice%2Falgorithms%2Fsorting%2Fselection-sort%2Ftutorial%2F&psig=AOvVaw1ZNGQtQsrvf9W5AjHklV8i&ust=1531205653972535)
