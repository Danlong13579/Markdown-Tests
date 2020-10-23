# Markdown Cheat Sheet 

<!-- Headings -->
<!-- H1 and H2 com with line breaks -->
# H1 {#custom-id's}
## H2
### H3
#### H4
##### H5
###### H6

<!-- Paragraphs and new lines & Line breaks -->
Paragraphs with line breaks  
This is the second lin  

Before Line break  

---

After Line Break  

<!-- Bold or Strong Text -->
**Bold Text**  
__Bold Text__  
Center**Bold**Text  

<!-- Italic Text -->
*Italic Text*  
_Italic Text_  
Center*Italic*Text  

<!-- Strikethroughs -->
This is what a ~~Strikethroughs~~ looks like.  

<!-- Blockquote with Nested Blockquote -->

> Never give up, never surrender  
>
>> Jason Nesmith, Tim Allen 

<!-- List Types with Nested Lists -->
1. Ordered List Item
1. Ordered List Item
    1. Ordered List Item
    1. Ordered List Item
1. Ordered List Item

* Unordered List Item
* Unordered List Item
    * Unordered List Item
    * Unordered List Item
* Unordered List Item

<!-- Code Blocks -->
#### JSON
```Json
{
    "httpMethod": "GET",
    "queryStringParameters": {
        "Distance": "537",
        "Speed": "35"
    }
}
```

#### Javascript
```Javascript
exports.handler = asynce (event, context, callback) => {
    if (event.httpMethod === 'GET') {
        let res = {
            statusCode: 200,
            body: JSON.stringify({
                message: "GET request approved",
                eventLog: event
            })
        }
        return res
    }
}

```

<!-- Links, use %20 for spaces in URL tages -->
Serverless API is possible **[AWS Lambda](https://aws.amazon.com/lambda/)**  
Contact Me <Danlong13579@gmail.com>

<!-- Definition List -->
Serverless API  
: Serverless computing is a method of providing backend services on an as-used basis.

<!-- Tasks -->
- [X] Install VScode
- [X] Add extensions you need
- [X] Make a git repo
- [ ] Start makeing commits

<!-- Emoji -->
### Emoji
 :new_moon:	:waxing_crescent_moon: :first_quarter_moon: :waxing_gibbous_moon: :full_moon: :waning_gibbous_moon: :last_quarter_moon:	:waning_crescent_moon: