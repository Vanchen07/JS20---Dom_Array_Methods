how to use forEach, map, filter, sort, reduce

using the flex: 1 property

using fetch an async/await so that we don't have to use the .then method

because fetch is async (fetching happens in the backgroun) we have to put await in front of it so that it waits
till the request is dont; we put async in front of the function to indicate that its an async function

fetch returns a promise and have to call res.json to format into json. bc it's also async we have to also put
await in front of this