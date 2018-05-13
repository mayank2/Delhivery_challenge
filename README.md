# Delhivery_challenge
# Problem Statement Background:

High-value shipments such as mobile phones, watches, jewellery are usually at risk of sellers shipping a counterfeit product to the customer, or conversely, customers returning a counterfeit product back to the retailer, while keeping the original item for themselves. High-value shipments are hence typically scanned by an x-ray machine during different stages of transit wherein, and an operator manually checks each x-ray image to ensure that the item in the box matches its product description.

# Goal:

To automate the solution with computer vision

# Breaking down to small actionable modules to solve this huge problem:

100,000 product-names with their descriptions are given (Anything ranging from watches to iPhones to house hold lamps). ~110,000 images are given with their product descriptions and if their x-rays match (True -> X-Ray match the product description and False -> X-Ray donot match the product description) .

# Breaking down to small actionable modules to solve this huge problem:

1. Build a text classifier to classify product descriptions to their “Sub-Category” . Example: Moto-G is a mobile , Saree is women’s clothing etc [Note: Tried Category based classification , got about 30%-40% accuracy, which was not very optimal]
2. Build an image classifier to check if the x-ray match their Sub-Category
