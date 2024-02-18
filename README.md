# Marketing-Mix-Modeling

**Published on RPubs** <br>

Link to Project: https://rpubs.com/Petermei0617/MMM <br>
OR <br>
Access the Rmarkdown file (Files needed: ***MMM regression dataset.csv***) <br>


This project was developed using data supplied by MMA, a consulting firm that specializes in marketing mix models. The purpose of this project is to understand how sales for Brand C relate to factors in the marketplace (own marketing efforts, others’ marketing efforts, environmental factors). This information could then be used to (i) assess the relative impact of different elements of the marketing mix and (ii) volume forecasting.

This is an integrated dataset with 179 weeks (Feb 2000 – Jul 2003) of observations for a variety of marketing mix variables. Brand C is one of the big players in a fairly commoditized product category. Brands R, E, P and U are some of the other brands in the category. Brand C and U are owned by the same company. Some of the measures in the dataset should look familiar, while others may be new. The key dependent variable in the dataset is equivalent units sales volume. You have selling price information for brands C, E, and P. The variable disacv_c not only measures how deep of a discount was offered for brand C, but also how prevalent that discount was across sales outlets.

A unique measure of promotional activity included in the dataset is expressed in terms of coupon valuation within an FSI drop, and how big the coupon drop was (in terms of circulation). This measure is reported as two variables for brand C contingent on holiday or non-holiday time periods. The dataset also has information about coupon drops for competitors R and E.

Information from Nielsen Media Research is incorporated into the dataset as TV GRP information for commercials featuring brands C and U. A gross rating point (GRP) is a variable used to measure the “impact” of television advertising. There is also an indicator variable for the thematic focus of the television advertising message.

The dataset also includes information about the prevalence of brand C’s bonus pack offering, a measure of line length per store expressed as rolling average of SKU’s per store, and (using panel data) percent share of brand C that is sold through Wal*Mart.

<br>

### Definitions of variables in dataset:

**week**: Week of observations <br>
**weeknumber**: Week number <br>
**month**: Month <br>
**year**: Year <br>
**eq_volum_c**: Equivalent unit sales volume for brand C (the dependent variable) <br>
**disacv_c**: Brand C %ACV * % Discount (This variable captures depth of price discount and how prevalent it was. That is, weighted average price discount) <br>
**bonusacv**: %ACV for stores in which brand C bonus pack had sales <br>
**price_c**: Brand C price per equivalent unit (non promoted price) <br>
**price_e**: Brand E price per equivalent unit (non promoted price) <br>
**price_p**: Private label price per equivalent unit (non promoted price) <br>
**tvgrp_c**: Brand C TV GRPs (GRPs are reach TIMES frequency or the number of people viewing the commercial and how many times they see it.) <br>
**tvgrp_u**: Brand U TV GRPs (GRPs are reach TIMES frequency or the number of people viewing the commercial and how many times they see it.) <br>
**trustad**: Theme of Brand C TV advertising focused on the message “Trusted”. Included to indicate times when this ad ran. <br>
**fsi_holi**: Brand C Holiday FSIs (coupon value * circulation) <br>
**fsi_non**: Brand C Non-Holiday FSIs (coupon value * circulation) <br>
**fsi_comp**: Brand E or R FSIs (coupon value * circulation) <br>
**itemstor**: Number of Brand C items sold per store – rolling 13 week average <br>
**walmart**: Wal*Mart share

