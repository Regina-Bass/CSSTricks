# Chapter 1

## Maintainability
The purpose of the maintainability exercise is to minimize code duplication. You should not have to make 10 edits in many different rules just to enlarge a button. Maintainability.html gives an example of two buttons with flexible CSS. A big part of this is making metrics relational and non-absolute. The dependency should be demonstrated in the code itself. Yet some lengths, such as the 1px thickness of the border is left absolute purposefully, so it's important to know the distinction of when it's appropriate, or how to make the judgement call. However challenges in maintainability doesn't happen with just font or size changes, it happens with things such as color too. We need to be mindful of how to maintain code when we choose to change the background color of the body for example. It's not as simple as changing the background - it involves changing the border, and the text shadow and the box shadow (in our example). When we're working on code someone else has written or when there's a significant amount of elements we're working with, CSS flexibility becomes very important, and making code future-proof starts early in the design process.
<img src="maintainability.jpeg" alt="Image of Maintainability Code output" />