# assessmentsftk
Gets a lists of products and returns the products grouped by category


This endpoint uses POST and only accepts an array of jsons representing a product. For example:
[
    {
        "description": "coca",
        "category": "drink"
    },
    {
        "description": "tea",
        "category": "drink"
    },
    {
        "description": "tea",
        "category": "DRINK"
    },
    {
        "description": "tea",
        "category": "food"
    }
]

Otherwise, it will return a MediaTypeNotAllowed or a BadRequest Response
