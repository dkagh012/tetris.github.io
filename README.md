<span>
<h2> 테트리스 게임
<img src="https://img.shields.io/badge/Bitrise-black?style=flat-square&logo=Bitrise&logoColor=white">
 </h2>
</span>
 <span>
<img src="https://img.shields.io/badge/HTML5-FFCA28?style=flat-square&logo=HTML5&logoColor=white">
<img src="https://img.shields.io/badge/CSS-004088?style=flat-square&logo=CSS&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=JavaScript&logoColor=white">
<img src="https://img.shields.io/badge/Visual Studio-0094F5?style=flat-square&logo=Visual Studio&logoColor=white">
</span>

```ruby
function renderBlocks(moveType=" "){
    const {type, direction,top,left} =tempMovingItem;
    const movingBlocks = document.querySelectorAll(".moving");
    movingBlocks.forEach(moving=>{
        moving.classList.remove(type, "moving"); 
    })
```
