# Uladzislau Baranouski
## Contact Info:
* **Phone:** +995 551 58 98 67
* **Email:** remenkton@gmail.com

## About me:
37 years. Originally from Belarus. Currently working as a Senior QA engineer in Exadel. 
I took these courses to better understand working with Git, HTML, CSS

## Skills:
* **Primary Skill:**
  + Manual QA
* **Programming Languages:**
  + JavaScript
* **Data Formats:**
  + JSON
  + XML
* **Tools:**
  + Jira
  + Kibana
  + Kafka
  + Postman 

## Code Example:
```
try
{
const numbers = [1, 2, 3, 4, 1];
const count = countOfOccures(numbers, 1);
console.log(count);
}
catch(e)
{
console.log(e);
}
function countOfOccures (array, searchElement) {
  if (Array.isArray(array) !== true)
  throw new Error ('Some Error');
  return array.reduce ((accumulator, current) => {
    const occurence = (current === searchElement) ? 1 : 0;
    return accumulator + occurence;
  },0 );
}