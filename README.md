# gut_microbiome_index
This repository contains the scripts and an algorithm for clustering gut microbiome compositions using dimensionality reduction and various feature selection techniques. This project focuses on clustering microbioal populations and visualizing their structures using various ML models. 

Examples to use the GMClust Algorithm
# Example usage
# otu, taxonomy, metadata = load_data('otu.csv', 'taxonomy.csv', 'metadata.csv')
# otu_filtered = filter_top_species(otu)
# diversity_indices = compute_diversity_indices(otu_filtered)
# combined_data = pd.concat([otu_filtered, diversity_indices], axis=1)
# clusters = apply_dbscan_clustering(combined_data)
# cluster_eval = evaluate_clusters(combined_data, clusters)
# visualize_clusters(combined_data, clusters, metadata)
