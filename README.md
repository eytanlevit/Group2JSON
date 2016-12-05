# Group2JSON
Export Facebook groups data to JSON

```
{
  posts: [
    {
      url: "http://www.facebook.com/groups/hashavua/posts/asdasd",
      created: "2015-03-25T12:00:00",
      lastComment: "2015-03-25T12:00:00",
      member: 1234,
      text: "היי חברים, יש לי שאלה",
      tags: ["פיתוח","עיצוב"],
      reactions: {
        total: 10,
        likes: 9,
        hearts: 1,
        angry: 0,
        wow: 0,
        cry: 0
      },
      comments: [
        {
          member: 1234,
          text: "הנה התשובה",
          replies: [
            {
              member: 12345,
              text: "המון תודה",
            }
          ]
        }
      ]
    }
  ],
  members: [
    {
      id: 123123,
      name: "Shimi Tavori",
      profilePic: "http://...",
      memberSince: 20-12-2016
    },
  ]
}
```
