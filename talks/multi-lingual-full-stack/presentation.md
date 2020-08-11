# Today

- What it means to be a multi-lingual or full-stack developer, based on my experience and observations
- I'd like to give some insight about why you may want to follow different paths, including the pros/cons, as well as how you might do it.

---

# Who

me: Made a career out of not wanting to pigeon-hole myself

---

# What: XPath

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

# What: SQL

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

# What: Rust

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
- "knowing the layout of the room"

---

# Why

- Spotting and re-using Patterns
- Perspective: "Computers are shit" ( :-) )
- "Bootstrap and Switch"
- Problem-focussed
- Choosing the right language for the job
- Building a Robust Company

---

# How

- Try experiments
  - example: Svelte, React
- Characterise options
  - "Pigeon-hole test": power vs culture
- Try to "feel the grain"
  - "this would be easier / better in Language X / Layer Y"
- Be a librarian / router for others

---

# Why Not

- Never the "best" at anything
- Hard for other people to understand what you do
  - you are the Elephant surrounded by the Blind men
- Can be easy to get distracted by too many options
- Can get confused
  - example: C# `yield` != Python generator

---

# Closing

- This is an option for a way to work, not a recommendation for everyone.
  - Being a specialist is still totally fine.
- However: please be proficient in at least two languages.
  - 2 is very different to 1
  - Avoid being a Foo programmer.
  - Drop your prejudices (something I still struggle with)
