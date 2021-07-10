# scRNA-seq Dashboard Prototype

This prototype implements the framework for buiding a web-based scRNA-seq data dashboard for interactive interpretation and idea exploration. In the backend, the app aggregates raw scRNA-seq gene-cell matrix into a high level gene expression data. In this typical case, the single cell expression data of the gene of interest was imputed from the matrix by MAGIC and then grouped according to their cell types. Violin plots were exploited to visualize the expression profiles across cell types. Finally, a dashboard is created to serve the computed data.

This app enables reordering the violinplot to generate the final figure that best emphasizes the biological meaning. In addition, a preliminary implementation for caching app running data in the user's browser was also tested. Although this example is a simplified user's case, new functionalities can be readily plugged into the existing framework to expand its usage. Check more information from the notebook and the sample usage clip.

<video width="320" height="240" controls>
  <source src="example.mov" type="video/mp4">
</video>
