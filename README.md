# Analyzing-Molecular-Properties-Dataset-from-PubChem

This project is designed to analyze molecular property data obtained from PubChem using Python. The dataset contains various molecular properties such as Molecular Weight and LogP for selected drug-like compounds such as Aspirin and Paracetamol. The assignment is divided into several steps, which include data loading, inspection, cleaning, and visualization of trends between molecular properties.

Dataset Link
Download the dataset from the following link:

PubChem Molecular Properties Dataset

Assignment Steps
1. Load the Dataset into a Jupyter Notebook using Pandas
First, the dataset is loaded into a Pandas DataFrame for easy manipulation and analysis.

2. Inspect the Data
After loading the dataset, inspect the columns, data types, and check for missing values. This is essential for understanding the structure and cleaning up any inconsistencies.

3. Perform Basic Data Cleaning
Handle missing values, if any, and ensure that the data is in a usable format. This may include removing duplicates or converting data types.

4. Visualize Property Trends
Molecular Weight vs LogP: A scatter plot showing the relationship between molecular weight and LogP value for the compounds.

LogP vs Compound Name: A bar plot or scatter plot showing the LogP values for different compounds.

5. Add Clear Labels and Titles to Your Plots
Ensure that all visualizations are clearly labeled with appropriate titles and axis labels for better understanding.

6. Bonus (Optional)
Explain how these molecular properties influence solvent selection in drug development.

Bonus (Optional): Impact of Molecular Properties on Solvent Selection in Drug Development
In drug development, selecting the right solvent is crucial for optimizing the solubility, bioavailability, and stability of a drug. The molecular properties of compounds, such as Molecular Weight and LogP, play a significant role in guiding this selection. Here's how these properties influence solvent choice:

1. Molecular Weight (MW):
Definition: Molecular weight refers to the mass of a molecule, calculated by adding the atomic masses of all atoms in the molecule.

Impact on Solvent Selection:

Solubility: Generally, smaller molecules (lower molecular weight) are more soluble in organic solvents, while larger molecules (higher molecular weight) may require polar solvents.

Viscosity: Larger molecules tend to have higher viscosities, which may necessitate solvents with specific viscosities for proper dissolution.

Stability: High molecular weight drugs might have poor stability in some solvents, requiring solvents that are chemically inert and capable of maintaining the drug’s structure during storage or formulation.

2. LogP (Octanol-Water Partition Coefficient):
Definition: LogP measures the hydrophobicity of a compound, calculated as the logarithm of the ratio of concentrations of a compound in octanol (lipophilic phase) to water (hydrophilic phase).

Impact on Solvent Selection:

Hydrophilic vs. Lipophilic Compounds:

High LogP (Lipophilic): Drugs with a high LogP value are more hydrophobic and are better solubilized in nonpolar solvents (e.g., oils, alcohols). Such compounds may require organic solvents like ethanol or propylene glycol for formulation.

Low LogP (Hydrophilic): Drugs with a low LogP value are more hydrophilic and dissolve better in polar solvents like water or aqueous buffers. These are typically water-soluble drugs used in oral or intravenous formulations.

Formulation Development: Understanding LogP helps in determining the right solvent for achieving the desired formulation properties, such as dissolution rate, stability, and bioavailability.

3. Solvent-Solute Interaction:
Hydrogen Bonding: Some solvents can form hydrogen bonds with drug molecules (especially those with functional groups like -OH, -NH2). This can improve solubility but may also affect drug stability and activity.

Polarity Matching: Polar compounds will typically dissolve better in polar solvents (e.g., water, ethanol), while non-polar compounds prefer non-polar solvents (e.g., chloroform, hexane).

4. Solvent Influence on Drug Delivery:
Bioavailability: The solvent can influence how a drug is absorbed by the body. Drugs that are poorly soluble in water may need to be formulated with solvents that enhance solubility to improve absorption in the gastrointestinal tract.

Formulation Consistency: Solvents are essential in ensuring consistent drug concentrations in pharmaceutical formulations, whether in tablets, capsules, or injectables. The molecular properties guide the selection of solvents that can maintain the drug’s stability and efficacy over time.

5. Considerations for Drug Development:
Environmental and Safety Aspects: Solvent selection must also account for environmental concerns and safety. Non-toxic, biocompatible, and environmentally friendly solvents are increasingly preferred, especially for drugs intended for long-term use.

Regulatory Requirements: Solvent use is often regulated, and solvents in final drug products must meet stringent guidelines for purity and permissible residue levels.

Conclusion
Molecular properties like Molecular Weight and LogP are fundamental in the selection of appropriate solvents during drug development. By understanding how these properties influence solubility, bioavailability, and stability, pharmaceutical scientists can choose solvents that not only optimize the drug's performance but also ensure safety, efficacy, and regulatory compliance. This process is critical for developing high-quality drugs that can be safely administered to patients.
