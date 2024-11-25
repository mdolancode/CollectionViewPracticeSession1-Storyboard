# Step-by-Step Guide: UICollectionView Implementation
## Option 1: Using Storyboard

1. Add a UICollectionView to Storyboard:
* Open Main.storyboard and drag a UICollectionView onto your view controller.
* Set constraints to pin it to the edges of the view.

2. Add a Flow Layout:
* Select the UICollectionView and set the layout to UICollectionViewFlowLayout for a simple grid layout.

3. Create a Prototype Cell:
* In the storyboard, add a prototype cell to the UICollectionView.
* Set a reuse identifier for the cell (e.g., "CollectionViewCellIdentifier").

4. Connect UICollectionView to Code:
* Create an IBOutlet for the UICollectionView in your view controller.
* Connect the data source and delegate to the view controller in the storyboard.

5. Conform to Protocols:
* In ViewController.swift, conform to UICollectionViewDataSource and UICollectionViewDelegate.
* Implement required methods like numberOfItemsInSection and cellForItemAt.

6. Customize the Layout:
* Adjust the layout properties such as item size, spacing, and scrolling direction within the storyboard inspector.

7. Create willDisplay & didEndDisplay Methods
* Repeat steps from tableView
