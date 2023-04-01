Most core web frameworks do not come with an opinionated way of fetching or updating data in a holistic way. Because of this developers end up building either meta-frameworks which encapsulate strict opinions about data-fetching, or they invent their own ways of fetching data. This usually means cobbling together component-based state and side-effects, or using more general purpose state management libraries to store and provide asynchronous data throughout their apps.

server state:

Is persisted remotely in a location you do not control or own
Requires asynchronous APIs for fetching and updating
Implies shared ownership and can be changed by other people without your knowledge
Can potentially become "out of date" in your applications if you're not careful