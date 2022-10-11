---
title: BMAK Chapter 2
summary: Discusses aggregate demand and the derivation of the IS curve.
authors: ["Binder"]
tags: ["sample tag"]
categories: ["lecture"]
date: "2019-02-05T00:00:00Z"
slides: bmak
---

# Chapter 2: Aggregate demand

---

## IS curve

The IS-curve ("IS" denoting investment equal to saving) renders for all possible levels of the interest rate the level of **output at which output supply is equal to aggregate demand**.

The IS-curve together with a relationship determining the interest rate, inter alia as a function of the level of output (this relationship will come from the financial sector), will later allow us to obtain the overall short-run macroeconomic outcomes for output, the interest rate, the components of aggregate demand and the exchange rate.

Let us derive and analyze the IS-curve.

---

Setting output produced equal to desired aggregate demand, we have:

$$
\begin{align}
Y &= DD \\\
\&= C_0 + C_y  (Y-T)-C_r\cdot r \\\
\&+ I_0-I_r r \\\
\&+ G_0 + G_y(\bar Y-Y) \\\
\&+ TB_0 + TB_{ex} (Y-T) - TB_im(Y-T)+TB_{\varepsilon}\cdot\left[\varepsilon_0-\varepsilon_r\cdot(r-r*)\right]
\end{align}
$$

---

## Code Highlighting

Inline code: `variable`

Code block:

```python
porridge = "blueberry"
if porridge == "blueberry":
    print("Eating...")
```

---

## Math

In-line math: $x + y = z$

Block math:

$$
f\left( x \right) = \;\frac{{2\left( {x + 4} \right)\left( {x - 4} \right)}}{{\left( {x + 4} \right)\left( {x + 1} \right)}}
$$

---

## Fragments

Make content appear incrementally

```
{{%/* fragment */%}} One {{%/* /fragment */%}}
{{%/* fragment */%}} **Two** {{%/* /fragment */%}}
{{%/* fragment */%}} Three {{%/* /fragment */%}}
```

Press `Space` to play!

{{% fragment %}} One {{% /fragment %}}
{{% fragment %}} **Two** {{% /fragment %}}
{{% fragment %}} Three {{% /fragment %}}

---

A fragment can accept two optional parameters:

- `class`: use a custom style (requires definition in custom CSS)
- `weight`: sets the order in which a fragment appears

---

## Speaker Notes

Add speaker notes to your presentation

```markdown
{{%/* speaker_note */%}}

- Only the speaker can read these notes
- Press `S` key to view
  {{%/* /speaker_note */%}}
```

Press the `S` key to view the speaker notes!

{{< speaker_note >}}

- Only the speaker can read these notes
- Press `S` key to view
  {{< /speaker_note >}}

---

{{< slide background-image="/media/a.jpg" >}}

## Custom Slide

Customize the slide style and background

```markdown
{{</* slide background-image="/media/boards.jpg" */>}}
{{</* slide background-color="#0000FF" */>}}
{{</* slide class="my-style" */>}}
```

---

## Custom CSS Example

Let's make headers navy colored.

Create `assets/css/reveal_custom.css` with:

```css
.present section h1,
.present section h2,
.present section h3 {
  color: navy;
}
```

---

# Questions?

[Ask](https://discord.gg/z8wNYzb)

[Documentation](https://wowchemy.com/docs/content/slides/)
