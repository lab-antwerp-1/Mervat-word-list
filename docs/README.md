<!-- BEGIN TITLE -->

# DOCS

<!-- END TITLE -->

<!-- BEGIN TREE -->

> [interactive graph](./dependency-graph.html)

![dependency graph](./dependency-graph.svg)

<!-- END TREE -->

<!-- BEGIN TOC -->

- public
- src
  - components
    - [render-list.js](#\client\src\components\render-listjs)
  - handlers
    - [input-word.js](#\client\src\handlers\input-wordjs)
    - [sort-words.js](#\client\src\handlers\sort-wordsjs)
  - init
    - [index.js](#\client\src\init\indexjs)
  - listeners
    - [input-word.js](#\client\src\listeners\input-wordjs)
    - [sort-words.js](#\client\src\listeners\sort-wordsjs)
  - logic
    - [is-word.js](#\client\src\logic\is-wordjs)
    - [sort-strings.js](#\client\src\logic\sort-stringsjs)
- styles
- [data.js](#\client\datajs)

---

<!-- END TOC -->

<!-- BEGIN DOCS -->

# /public

---

# /src

## /components

<details><summary><a href="../..\client\src\components\render-list.js" id="\client\src\components\render-listjs">..\client\src\components\render-list.js</a></summary>

</details>

---

## /handlers

<details><summary><a href="../..\client\src\handlers\input-word.js" id="\client\src\handlers\input-wordjs">..\client\src\handlers\input-word.js</a></summary>

<a name="inputWord"></a>

## inputWord

Entry point for users adding a word to the list.
It is called each time the user clicks the "add word" button.

| Param | Type               | Description                                          |
| ----- | ------------------ | ---------------------------------------------------- |
| event | <code>Event</code> | The event triggered when the user clicks the button. |

</details>

<details><summary><a href="../..\client\src\handlers\sort-words.js" id="\client\src\handlers\sort-wordsjs">..\client\src\handlers\sort-words.js</a></summary>

<a name="sortWords"></a>

## sortWords

Entry point for users sorting the list of words in this app.
It is called each time the input selection changes.

| Param | Type               | Description                                |
| ----- | ------------------ | ------------------------------------------ |
| event | <code>Event</code> | The event triggered by changing the input. |

</details>

---

## /init

<details><summary><a href="../..\client\src\init\index.js" id="\client\src\init\indexjs">..\client\src\init\index.js</a></summary>

</details>

---

## /listeners

<details><summary><a href="../..\client\src\listeners\input-word.js" id="\client\src\listeners\input-wordjs">..\client\src\listeners\input-word.js</a></summary>

</details>

<details><summary><a href="../..\client\src\listeners\sort-words.js" id="\client\src\listeners\sort-wordsjs">..\client\src\listeners\sort-words.js</a></summary>

</details>

---

## /logic

<details><summary><a href="../..\client\src\logic\is-word.js" id="\client\src\logic\is-wordjs">..\client\src\logic\is-word.js</a></summary>

<a name="isWord"></a>

## isWord ⇒ <code>boolean</code>

Checks if a string is a word. A word contains only letters.

**Returns**: <code>boolean</code> - Whether or not the text is a word.

| Param | Type                | Description                      |
| ----- | ------------------- | -------------------------------- |
| text  | <code>string</code> | A string to check for wordiness. |

**Example**

```js
// ... write this!
```

</details>

<details><summary><a href="../..\client\src\logic\sort-strings.js" id="\client\src\logic\sort-stringsjs">..\client\src\logic\sort-strings.js</a></summary>

<a name="sortStrings"></a>

## sortStrings ⇒ <code>Array.&lt;string&gt;</code>

Sorts an array of strings in different ways.
It does not modify the argument (no side-effects).

**Returns**: <code>Array.&lt;string&gt;</code> - A new sorted array containing the same strings as toSort.

| Param      | Type                              | Default                                     | Description                                                                                                                                                                                                                                                                                                             |
| ---------- | --------------------------------- | ------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [toSort]   | <code>Array.&lt;string&gt;</code> | <code>&#x27;&#x27;</code>                   | The array of strings to sort.                                                                                                                                                                                                                                                                                           |
| [sortType] | <code>string</code>               | <code>&quot;&#x27;oldest&#x27;&quot;</code> | How to sort the strings, 6 options. - oldest: from oldest to newest. - newest: from newest to oldest. - shortest: from shortest to longest. - longest: from longest to shortest. - a: alphabetical order. - z: reverse alphabetical order. If the sortType is not one of these 6 options, a copy of toSort is returned. |

**Example**

```js
// ... write this!
```

</details>

---

---

# /styles

---

<details><summary><a href="../..\client\data.js" id="\client\datajs">..\client\data.js</a></summary>

<a name="data"></a>

## data

**Properties**

| Name  | Type                              | Description                                                         |
| ----- | --------------------------------- | ------------------------------------------------------------------- |
| words | <code>Array.&lt;string&gt;</code> | An array of words that the user has provided.                       |
| sort  | <code>string</code>               | A string indicating the order string should be displayed in the UI. |

</details>

<!-- END DOCS -->
