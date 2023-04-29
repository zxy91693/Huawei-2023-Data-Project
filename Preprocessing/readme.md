# Preprocessing

## Unique Data
Drop the dupilcate of (U_id,I_id,label)

## Feature Preprocessing
1.  Mask sparse and small ratio of ramdon feature value
2.  Classify the continuous features with bins

## Split Dataset
1.  Drop sparse user
2.  Split Dataset into Train Valid(wuwi,wuci,cuwi,cuci) Test(wuwi,wuci,cuwi,cuci)

## Calculate unnormalized popularity
 ![Image text](https://github.com/zxy91693/Huawei-2023-Data-Project/blob/main/images/Unnormalized_popularity.PNG)

## Calculate normalized popularity
 ![Image text](https://github.com/zxy91693/Huawei-2023-Data-Project/blob/main/images/Normalized_popularity.PNG)

## Remap feature and save

## Application
Assume the original score of DCN model output before sigmoid is S with popuarity P. The PDA output is $$S' = S \times P^{\gamma}$$
