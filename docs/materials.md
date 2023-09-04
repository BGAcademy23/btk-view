# Session Materials

## Links

- [Slides](https://docs.google.com/presentation/d/1rIJTyVkKkw_VEW1osIK7-WAbevRG7gUZ9NzQXGK7wKA/edit?usp=sharing){: target="_blank" }
- [Cheat Sheet](BTK-cheatsheet-2023-05-12.pdf)

## Top Tips

- Copy the URL in the browser bar to save/share a BTK plot
- Remove everything after "?" in the browser URL to reset the plot

### Datasets
- use search bar
- Click headers to sort results.
- Click a row to view an assembly.
- Type in the box at the top of each column to filter assemblies
- **Customise table** to add useful columns

### Views Menu
- blob, table (taxonomy assignment), busco, report

### Filters
- **WHAT is shown**, allow you to keep contigs of interest
- Numeric (GC, Coverage, BUSCO count)
- Categorical: Taxonomy rules (Buscogenes, Buscoregions, Bestsumorder) + Taxon_rank (phylum, class, order)
- Selection: point and click - then use selection menu on top

### Settings
- **HOW it is shown**
- plot shape: I always change to Circle, but squares/hex/kites are useful when large numbers of contigs
- reducer: histograms/bars on the sides
- axis: change these to zoom
- static/interactive thresholds

## Exercises

A. **_Didymella arachidicola_**

1. Find a public genome assembly
    - Use the [BlobToolKit (BTK) public genomes viewer](https://blobtoolkit.genomehubs.org/view/) to find <em>Didymella arachidicola</em> - Peanut Leaf Blotch
    - Use the Datasets top menu - (a) Search Bar and the (b) Tree Browser (click on numbers) > Eukaryota > Fungi > Ascomycota > Dothideomycetes > Pleosporales > Didymellaceae > Didymella (tree is not up to date)

2. GC and Coverage filters
    - Start with <em>Didymella arachidicola</em> again [https://blobtoolkit.genomehubs.org/view/Didymella%20arachidicola/dataset/WOCF01/blob](https://blobtoolkit.genomehubs.org/view/Didymella%20arachidicola/dataset/WOCF01/blob)
    - Use the Filters top Menu and change the GC and Coverage so that EXACTLY 1 contig is shown
    - Use the little "reset" link to reset each filter afterwards
    - Use the browser URL to reset the whole plot

3. Change the numerical axes
    - gc filter -> click the y axis button
    - _cov filter -> click the x axis button

4. Categorical Filters
    - Use the Filter **buscogenes_phylum** to only show the Proteobacteria
    - Change to **buscogenes_family** to identify the family of the Proteobacteria
    - Change the plot to show the family (Click on the "category" button to the right of the **buscogenes_family** filter)

5. Use the Table view
    - Only filtered contigs are shown as rows
    - Activated filters are shown as columns
    - Coloured categories match the plot
    - Click on colored categories to see blast hits

B. **_Casuarina equisetifolia_** coastal she-oak

1. Find it (Hint: Top Menu Datasets)
2. Change the shape to circle (Hint: Settings > Shape)
3. What is the main cobiont? Is it a contaminant?
4. What is the second higher coverage set of green circles? (Hint -> Isolate it, use the Table view, click to see blast hits)
5. There are three _cov filters from three sequencing libraries, plot the first on the x axis and the second on the y axis
6. Select the "0" coverage contigs using a mouse
7. Filter -> Selection -> Activate
8. Lists -> name the current selection and click Create List
9. Click on created list and "Full List" to Download

C. **_Hypsibius dujardini_** tardigrade controversy

1. Find this assembly LMYF01.1
2. Change the shape to circles
3. How many separate organisms do you think there are?
4. Zoom in to the main blob
5. How would you identify what is a contaminant?

D. **_Gymnoscelis rufifasciata_** Double striped pug (moth)

1. Find the assembly - how many read sets does it have mapped?
2. Filters > Plot gc on y axis, proportion on x axis
3. Settings > Shape > Plot Connected Windows
4. Settings > Shape > Plot Grid
5. Settings > Plot style > Lines




