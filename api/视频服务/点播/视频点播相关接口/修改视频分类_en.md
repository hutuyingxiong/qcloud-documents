## 1. API Description
 
Domain: vod.api.qcloud.com
API name:  ModifyVodClass

Modify the category of video files

 

## 2. Input Parameters
 
<table class="t"><tbody><tr>
<th><b>Parameter Name</b></th>
<th><b>Required</b></th>
<th><b>Type</b></th>
<th><b>Description</b></th>
<tr>
<td> fileId
<td> Yes
<td> String
<td> Video ID
<tr>
<td> classId
<td> Yes
<td> Int
<td> Category ID
</tbody></table>

 

## 3. Output Parameters
 
<table class="t"><tbody><tr>
<th><b>Parameter Name</b></th>
<th><b>Type</b></th>
<th><b>Description</b></th>
<tr>
<td> code
<td> Int
<td> Error code. 0:  Succeeded, other values:  Failed
<tr>
<td> message
<td> String
<td> Error message
</tbody></table>

 

## 4. Example
 
Input
<pre>
  https://domain/v2/index.php?Action=ModifyVodClass
  &fileId=2721945854681023354
  &classId=45
  &<a href="https://www.qcloud.com/doc/api/229/6976">Common request parameters</a>
</pre>
Output
```

{
    "code" : 0,
    "message" : "",
}

```



