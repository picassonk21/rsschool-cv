# Egor Borisevich

telegram: *[t.me/picassonk21](t.me/picassonk21)*  

phone: *+375447947723*  

email: *[picassonk21@gmail.com](picassonk21@gmail.com)*

## Objective  
I'm participating in the course to gain theoretical knowledge and practical skills of programming in javascript, related skills necessary for a junior developer, and i hope to make new interesting acquaintances.

## About me

My global goal is to change my profession, find a job in the IT and become successful here. i can say that my strong poing is the mathematical mindset.I love mathematics from school, participated in all stages of the republican olympiad in mathematics and received diplomas of various degrees. I also consider my work experience in another field (banking) to be my advantage, because my intention to become a programmer was formed during three years of work in the bank. and now i know exactly what i want.

## Education

* **Belarusian State Economic University**, faculty of finance and banking, bachelor's degree (2015-2019)  

* course *"Modern Front-End using JavaScript and HTML5"*, Belhard Academy (2020 november - 2020 december)

## Skills

i started learning programming about a year ago. My first language was python. I think my basic knowledge is pretty good. Then i taught html, css, mastered the layout. For about four months i have been teaching javascript and it's framework React.

## Code examples

My last training project (it's in progress) is available *[here](https://github.com/picassonk21/shop_demo)*  

Below i will post a piece of code from this project, thunk named *setProductsData*:

```
export const setProductsData = () => dispatch => {
    shopAPI.getProducts()
    .then(
        response => {
            if(response.status === 200) {
                dispatch(setProducts(response.data));
                dispatch(setCategories(response.data))
            }
        }
    )
}
```

## Work experience

* **MTBank, 2018 - present**

Minsk, Belarus

Forex specialist

## English

According to the passed test on *[training.by](training.by)* my english level is A2+