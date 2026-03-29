# Classification-ML-Project

## Classification ML Project using Logistic Regression

Using the Indian Liver Disease dataset, we would like to develop a logistic regression machine learning model where the output variable of interest would be a binary response variable labelled `Selector'. This column contains records of 416 patients diagnosed with liver disease and 167 patients without liver disease.
There are 10 variables per patient: age, gender, total Bilirubin, direct Bilirubin, total proteins, albumin, A/G ratio, SGPT, SGOT and Alkphos. Of the 583 patient records, 441 are male, and 142 are female.

## Clinical variables
Below is a brief description of each clinical variable and how it helps predict liver disease;
- Bilirubin is a yellowish pigment formed during the breakdown of hemoglobin in red blood cells. It is processed in the liver and excreted in bile. There are two types of bilirubin that are clinically signficant in predicting the presence of liver disease; Total Bilirubim (TB) and Direct Bilirubin (DB).
  - Total bilirubin is the sum of direct bilirubin (conjugated) and indirect bilirubin (unconjugated) in the blood.
  - Direct bilirubin (conjugated) is bilirubin that has been processed by the liver, becoming water-soluble whereas Indirect bilirubin (unconjugated) has not yet been processed by the liver and is not water-soluble. The normal range is approximately 0.3 to 1.2 mg/dL in adults. Elevated levels of bilirubin, especially direct bilirubin, are signficant markers for liver dysfunction and biliary system issues.

- Alkaline Phosphotase (Alkphos) is an enzyme found in several tissues throughout the body, with the highest concentrations in the liver, bones, kidneys and biliary tract. It plays an important role in breaking down proteins and is most active in alkaline conditions. The
normal range in adults is 44 to 147 IU/L. Elevated levels are often associated with conditions affecting the liver, bile ducts, or bones.

- Alanine Aminotransferase (Sgpt) and Aspartate Aminotransferase (Sgot) are enzymes found in various tissues of the body, but they are most abundant in the liver. They play a role in amino acid metabolism, helping convert amino acids into energy or other compounds. Alanine Aminotransferase is predominantly found in liver cells (hepatocytes), with smaller amounts in muscles and kidneys. It converts alanine and alpha-ketoglutarate into pyruvate and glutamate. The normal range for adults is ~7 to 56 units per liter (U/L). When liver cells are damaged or in amed, it leaks into the bloodstream, making it a sensitive marker for liver injury.
Aspartate Aminotransferase is predominantly found in liver cells (hepatocytes), with smaller amounts in muscles and kidneys. It catalyzes the conversion of aspartate and alpha-ketoglutarate to oxaloacetate and glutamate. The normal range for adults is ~10 to 40 units per liter (U/L). When elevated, it can indicate muscle injury or heart disease.

- Total Proteins (TP) refers to the total concentration of proteins in the blood, primarily consisting of:
1. Albumin: A protein produced by the liver, crucial for maintaining oncotic pressure (fluid balance) and transporting substances like hormones and drugs.
2. Globulins: A group of proteins involved in immune functions, blood clotting, and transportation. The normal range in adults is 6.0 to 8.3 g/dL. Low Total Protein (Hypoproteinemia) may indicate the presence of chronic liver disease, malnutrition or increased protein loss whereas High Total Protein (Hyperproteinemia) could be an indicator of dehydration chronic infections or infammation.

Albumin-to-Globulin (A/G) Ratio is total protein and liver disease marker that should range between ~1.2 to 1.5. A low ratio (<1) may indicate presence of chronic liver disease, where albumin synthesis is impaired and globulins increase. A high ratio (>1.5) may indicate dehydration and certain congenital conditions.
