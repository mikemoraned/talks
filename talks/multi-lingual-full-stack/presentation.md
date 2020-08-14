build-lists: true

# Today

- What it means to be a multi-lingual or full-stack developer, based on my experience and observations
- Some insight about why you may want to follow different paths, including the pros/cons, as well as how you might do it.

---

# Who

- me: Made a career out of not wanting to pigeon-hole myself
  - https://twitter.com/mike_moran
  - https://www.houseofmoran.com/

---

---

# What: Spotting Patterns

- An illustratative example to get us started

---

# What: XPath Example

```html
<ul>
  <li id="2">Bloop</li>
  <li id="1">Feep</li>
</ul>
```

```xpath
//li[@id = 2]//text() -> Bloop
//li[position() = last()] -> <li id="1">Feep</li>
```

[link]: http://xpather.com/oGNHCuAb

---

# What: SQL Example

```sql
SELECT CustomerName, Country
FROM Customers
WHERE City = 'Paris'
```

| CustomerName         | Country |
| -------------------- | ------- |
| Paris spécialités    | France  |
| Spécialités du monde | France  |

[link]: https://www.w3schools.com/sql/trysql.asp?filename=trysql_op_in

---

# What: Rust Example

```rust
fn main() {
    let a = [1, 0, 3];

    let iterated : Vec<_> =
        a.iter()
         .filter(|&i| *i != 0 )
         .collect();

    dbg!(iterated);                iterated = [1, 3]
}
```

[link]: https://play.rust-lang.org/?version=stable&mode=debug&edition=2018&gist=e773b55d2c6ee6ec22b434c3a59499ea

---

# What

- XPath `<->` SQL `<->` Rust?
- What's different / similar?

---

# Any Questions?

---

# Why: lower-level

- Spotting and re-using Patterns
  - know the layout of the room
- Problem-focussed
- Choosing the right language/library for the job
  - "Library-first Programming"

---

# Why: higher-level

- Gives Perspective: "All Computers are Shit" ( :-) )
- Bootstrap in X, Scale out in Y
- Building a Robust Company

---

# Any Questions?

---

# How

- Try experiments
  - example: Svelte, React
- Characterise options
  - "Pin-hole test": power vs culture
- Try to "feel the grain"
  - "this would be easier / better in Language X / Layer Y"
- Be a librarian / router for others, learn on the way

---

# Why Not

- Never the "best" at anything
- Hard for other people to understand what you do
  - you are the Elephant surrounded by the Blind men
- Can be easy to get distracted by too many options
- Can get confusing technically
  - example: C# `yield` != Python generator

---

# Any Questions?

---

# Closing

- This is an option, and not a recommendation for everyone.
  - Being a specialist is still totally fine
- However:
  - please be proficient in at least 2 languages; 2 is very different to 1
  - Avoid being a "Foo" programmer; drop your prejudices (something I still struggle with)

---

# Contact details

- For any questions / suggestions:
  - https://twitter.com/mike_moran
  - mike@houseofmoran.com
  - https://www.houseofmoran.com/
