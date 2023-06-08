---
marp: true
theme: default
size: 16:9

backgroundColor: #fff
style: |
    .columns {
    display: grid;
    grid-template-columns: repeat(2, minmax(0, 1fr));
    gap: 1rem;
    }

    section {
      font-size: 1.2em;
      justify-content: flex-start;
    }

    section::after {
      font-size: 0.6em;
      text-shadow: 1px 1px 0 #fff;
      left: 50%;
      transform: translateX(-50%);
      content: '[' attr(data-marpit-pagination) '/' attr(data-marpit-pagination-total) ']'
    } 

    footer {
      bottom: 10px
    }


footer: '![wl_footer](https://raw.githubusercontent.com/vbalbarin/presentations/main/assets/common/wl_slide_footer.png)'


---

# **{{ title }}**

{{ authorName }}
{{ date }}

---
<!-- paginate: true -->
<style>
blockquote {
    border-top: 0.1em dashed #555;
    font-size: 60%;
    margin-top: 50px;
}
sup {
  font-size: 65%;
}
</style>

## {{ slide1Title }}

1. {{ item1 }}
2. {{ item2 }}

---

## {{ slide2Title }}

{{ paragraphTextSlide1 }}

```bash
# code block
```

---

{{ untitledSlideContinuationOfPrecedingSlide }}

