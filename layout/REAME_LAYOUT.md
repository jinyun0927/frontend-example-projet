# Layout

## flex box layout based on media query

![image-20200625142619098](./image_readme/image-20200625142619098.png)

When the width is less than 576px, this page will change to the style "mobile first"

![image-20200625142808560](./image_readme/image-20200625142808560.png)



key point: 

```css
@media screen and (min-width: 576px){
    .main{
    	flex-direction: row;
    }
    .main .nav, .main .aside{
    	flex: 0 0 20vw;
    }
}
```



## Bootsrap layout

![image-20200626161406956](./image_readme/image-20200626161406956.png)



[Bootstap](https://getbootstrap.com/docs/4.5/getting-started/introduction/) is a mobile-first and reponsive front-end framwork. 

We can see in the following picture that the page style is automatically adjusted when we change the size of page.



![image-20200626161626454](./image_readme/image-20200626161626454.png)