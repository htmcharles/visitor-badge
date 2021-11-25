![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)  

[中文](https://github.com/hehuapei/visitor-badge/blob/master/readme_cn.md)

#### Project Home
> [https://visitor-badge.laobi.icu](https://visitor-badge.laobi.icu)

#### Usage
- default style

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge)

- customized left text (default is `visitors`)

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=MyPageVisitors)
```
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=MyPageVisitors)

- customized left text with a space between words

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=My%20Page%20Visitors)
```
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_text=My%20Page%20Visitors)

- customzied color

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green) 
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green) (left_color=red, right_color=green)

- customized color and left text

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=HelloVisitors)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=HelloVisitors) (left_color=red, right_color=green, left_text=HelloVisitors)

- customized color and a space between words in left text

```markdown
![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=Hello%20Visitors)
```

![visitor badge](https://visitor-badge.laobi.icu/badge?page_id=jwenjian.visitor-badge&left_color=red&right_color=green&left_text=Hello%20Visitors) (left_color=red, right_color=green, left_text=Hello%20Visitors)

#### Feature

- **2020.07.19**  
1. Daily data backup: Perform data backup and push to GitHub warehouse at 0 o 'clock per day  

- **2020.07.18**  
1. You can use parameter 'title' to change badge's title！  
**tips: The title Poor compatibility to chines**  
Official: [link](https://pypi.org/project/pybadges/)  
pybadges uses a pre-calculated table of text widths and kerning distances (for western glyphs) to determine the size of the badge. So Eastern European languages  may be rendered less well than Western European ones:  
and glyphs not present in Deja Vu Sans (the default font) may be rendered very poorly:  
pybadges does not have any explicit support for languages that are written right-to-left (e.g. Arabic, Hebrew) and the displayed text direction may be incorrect:  
 
- **2020.07.17**  
1. Change count-api to my own service, optimize the counting speed.   
2. It facilitates later functions (data analysis, data backup, etc.)

#### Fork From
> jwenjian: [https://github.com/jwenjian/visitor-badge](https://github.com/jwenjian/visitor-badge)
