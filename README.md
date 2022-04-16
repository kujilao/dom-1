# dom-dome预览
````
window.dom = {
    find(node) {
        return document.querySelectorAll(node)
    },
    style(node, name, value) {
        node.style[name] = value
    },
    each(nodeList, fn) {
        for (let i = 0; i < nodeList.length; i++) {
            fn.call(null, nodeList[i])
        }
    }
};
````
