# Grid Layout workshop

- Why “optimized for UI design”?
	- Differentiate between grid and table.
	- Look at what otgher spec say.
		- Flexbox does same
	- Because it is the main focus.
- Why is CSS defined in Abstract?
- Is subgrid still at risk?

## 2. Overview
- Should all terms be linked all of the time?
	- Group devided.
	- Concensus is only first should link
- Take out “analogous to flex items”
- I don't want to have to know to bake a cake if I want to make cookies.
- The ‘grid’ shorthand on the grid container allows setting all of these grid definition parameters at once.
- There is a logical order.
- Less technical?
- Use an ordered list for the steps to build the grid
- Simplify overview
- Add a diagram
- Strip out the how it does it.
- Use a list for the last paragraph

## 2.1 Background and Motivation
- Replace tools with technique
- Figures need numbers

## 2.2 Adapting Layout to Available Space
- use of intelligently in first sentence (replace?)
- The score area is aligned into the same column as the stats area.
- The controls area is centered in the same column as the game board.
- Remove values from figure 2 and 3
- Add one with values

## 3. Grid Layout Concept and Terminology
- “and an orthogonal set defining rows along the inline axis (the row axis). [CSS3-WRITING-MODES]” doubts about orthogonal
- Add a diagram to explain the axis and lines.
- Add arrow to axis to figure 7.
- Replace e.g. with “such as”: https://twitter.com/FriendlyAshley/status/730965648004653056
- Replace ie with “in other words”
- Check syntax highlighting on all code examples.
- Example 5
	- Language check
	- Remove? Doesn't make sense.
- Add diagrams to term definitions
- Add image of result to example 6

## 5.1
- Make all references link to REC
- max-content link to CSS4, last paragraph links to CSS3

## 5.3
- Change “overlarge”?
- Can we define a magic number for the clamping limit

## 6. Grid Items
- Example 10: Image should not have anonymous item styled
- Link to HTML example in text.

## 6.1
- Tomek to work on this

## 6.4
- “and z-index values other than auto create a stacking context even if position is static.”
	- Remove “even if position is static”
	- transform and opacity spec don't have the “even if” part
- Edge cases for the note about stacking context

## 7.1
- Add example for paragraph 2
- “If these properties don’t define any explicit tracks, the explicit grid still contains one grid line in each axis.”
	- Remove explicit in explicit tracks
	- Because it's not a technical term
- What is an explicit grid?
	- Is it an explicit number of tracks
	- Is it an explicit size of tracks
- 