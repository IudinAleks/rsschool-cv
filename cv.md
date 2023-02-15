# Iudin Aleksandr

![avatar](/img/avatar.jpg "Аватар")
***

## Frontend Developer

***

### Contacts

* **Location:** Volgograg, Russia
* **Email:** a.s.yudinmail@gmail.com
* **Telegram:** @IudinAleks
* **GitHub:** [IudinAleks](https://github.com/IudinAleks "GitHub")

***

### Skills

 * Javascript/ES5/ES6
 * HTML/CSS3
 * Node.JS/Express
 * React 

***

### Code example

**Kata:** Fun with trees: array to tree

```
function arrayToTree(array) {
  return (function nodeFromIndex(i) {
    if(array[i] === undefined)
      return;
    return new TreeNode(array[i], nodeFromIndex(i * 2 + 1), nodeFromIndex(i * 2 + 2));
  })(0);
};
```
