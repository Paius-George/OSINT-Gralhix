[‹ Back to all exercises](../README.md) · [Versiunea în limba română →](README.ro.md)

---

# Bonus Exercise: OSINT Olympics 2026

In this photo-based exercise, we need to figure out the exact date the photo was taken.

<img width="714" height="513" alt="image" src="https://github.com/user-attachments/assets/a8991310-fc3b-4837-9c47-bf6d9a4cb56c" />

# Solution:

## Part 1. Clues and initial thoughts:

a. An arched structure, on which there is a panel displaying what is most likely the manufacturer's name: "MCH", a text "KL." (which we don't know the exact meaning of yet), the exact time, and the temperature.

b. Behind the arch, there is what appears to be a hair salon, which will help us confirm the geolocation.

c. Snow is visible around, indicating that the photo was most likely taken in December, January, or February.

d. The tags on the photo: #sooooocold #winter #pandemic. There is a strong emphasis on the fact that it was -9 degrees outside, and we are given another clue that will probably help us enormously later: #pandemic. Thus, we already know that the photo was most likely taken in one of the 3 previously mentioned months and during a pandemic.

## Part 2. Investigation using search engines:

To begin, since we don't have too much information to help with an efficient geolocation anyway, I searched for the keywords already seen on the panel: "MCH" and "KL.".

<img width="1496" height="1564" alt="image" src="https://github.com/user-attachments/assets/62a34182-38a9-4ff9-9420-1e7508d7e1cf" />


As can be seen, the first page of the search is not of much help since we only have results from Malaysia (which has a tropical climate). However, moving on to the second page, we arrive at the following interesting result:

<img width="1348" height="296" alt="image" src="https://github.com/user-attachments/assets/8b0cff64-a5ed-4798-bb7d-f3a779e6078c" />


[mch.dk](https://www.mch.dk) - A website from Denmark? This already sounds promising.

<img width="2530" height="1720" alt="image" src="https://github.com/user-attachments/assets/be091bbf-abfe-473c-bb5c-0018a28926d5" />


Being totally lost on the Home page, I just tried to look for the contact page to get more information later regarding possible locations.

<img width="1638" height="892" alt="image" src="https://github.com/user-attachments/assets/c467e48a-c658-4451-8089-6de9b234e0fa" />

## Part 3. Investigation using Google Maps:

Since `Østergade 37 7400 Herning` was the first location anyway and it was also repeated twice, I decided to start with it. Arriving exactly at what seems to be our location, as can be seen in the picture below:

<img width="2390" height="1678" alt="image" src="https://github.com/user-attachments/assets/ffea7478-b73a-43d0-8954-656cc9a83229" />
<img width="2530" height="1682" alt="image" src="https://github.com/user-attachments/assets/558a96d9-3009-4e30-9d71-9ca7fe16b1b3" />


However, the first noticeable problem is that the reference photo seems to have been taken a long time ago.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c4873edc-6800-4f02-9c6e-54e9ccc8ee4d" />

## Part 4. Location history and additional data:

The latest accessible date on Google Maps is 2012, but what should raise our suspicions is the fact that the hair salon is not in the background. Therefore, we will have to find the period when the salon was opened and closed, respectively, to get closer to the answer.

![alt text](Pasted_image_20260816010929.png)

In the red rectangle should be exactly the old hair salon, the current restaurant. I also underlined the exact address because it will be useful when we look for the salon's activity period. Until we get there, however, we need to find all the keywords, so we will need a Danish translation for the word **hairdresser/salon**.

<img width="2534" height="1714" alt="image" src="https://github.com/user-attachments/assets/a4da4d6a-d00d-42bd-b23c-5c3e27b1e2b2" />

Thus, we have the necessary tools to find out the hair salon's activity period: `Østergade 29, 7400 Herning`, `frisør`.

<img width="1354" height="536" alt="image" src="https://github.com/user-attachments/assets/b9602508-c664-4020-9164-c71342ba19f6" />


This is the result of the search using only the necessary keywords, and on one of the sites, it can be seen how the location was opened on 01.09.1990 and closed on 28.02.2010. The period seems quite large, but as far as we remember we had the #pandemic tag which indicates that the photo was taken between these dates, during a pandemic.

<img width="1964" height="1714" alt="image" src="https://github.com/user-attachments/assets/8f55b4ea-36e1-4972-9cf0-e5ea61f7f634" />

<img width="1898" height="640" alt="image" src="https://github.com/user-attachments/assets/c6e46805-5a11-4984-8cbe-e239f56f9272" />


From the first [result](https://en.ssi.dk/news/epi-news/2010/no-1---2010), it seems that the pandemic period was in 2009, and the virus name is: A(H1N1). Thus, from a period of almost 30 years, we have narrowed it down to 2009 and 2010 respectively. After a quick recall to the clues found before solving, we can summarize the following periods: December 2009, January 2010, February 2010, and the exact temperature of -9 degrees at 23:47.

<img width="1832" height="1532" alt="image" src="https://github.com/user-attachments/assets/c9f5d79a-9c57-4a4c-9691-72a8b1c53038" />


## Part 5. Weather data analysis:

For this, we can again use a basic search such as: `Herning weather history`.

<img width="1856" height="548" alt="image" src="https://github.com/user-attachments/assets/feb4ac8f-8944-4c44-8dd8-511b69726f75" />

<img width="2234" height="1190" alt="image" src="https://github.com/user-attachments/assets/04d5268d-d1ca-493c-b768-e4c38b20d5f8" />

Fortunately, the site already has a graph that doesn't force us to manually go through every day of December 2009. It can be seen underlined that on December 31 a temperature of -9 degrees Celsius was recorded.


The problem, however, is that we are interested in the exact temperature at 23:47 and it is clearly visible how it was exceeded.
Two days later, however, we reach the following result:

<img width="966" height="204" alt="image" src="https://github.com/user-attachments/assets/41d8332e-f252-45a2-ae4e-47b2834f9057" />


### Part 6. Conclusion:

The data confirms that the photo was taken, approximately, at the coordinates: `56°08'08.0"N 8°58'50.6"E`, on **January 2, 2010**.
