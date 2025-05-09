---
layout: page
classes: wide
---

<div style="position: relative; width: 100vw; margin-left: calc(-50vw + 50%); overflow: hidden;">

  <!-- Image -->
  <img src="/assets/images/NewYorkStreets.jpg" style="width: 100%; height: auto; display: block;" alt="NYC street">

  <!-- Dark overlay -->
  <div style="
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, 0.45); /* Adjust darkness here */
  "></div>

  <!-- Title text -->
  <h1 style="
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 3em;
    font-weight: bold;
    text-align: center;
    text-shadow: 2px 2px 8px rgba(0, 0, 0, 0.7);
    margin: 0;
    padding: 0 20px;
    width: 100%;
    box-sizing: border-box;
  ">
    Navigation of the New York City jungle of restaurants
  </h1>

  <!-- Caption -->
  <figcaption style="
    position: absolute;
    bottom: 10px;
    right: 20px;
    font-style: italic;
    font-size: 0.9em;
    color: white;
    text-shadow: 1px 1px 4px rgba(0,0,0,0.6);
  ">
    Photo by CONTEXT[1]
  </figcaption>

</div>

<div>
<br>
New York City is globally celebrated for its extraordinary culinary diversity. From high-end dining experiences in Manhattan to vibrant street food scenes in Queens, the city offers options to suit every palate and budget. Yet for tourists unfamiliar with the city's health inspection system, deciding where to eat can be overwhelming. With up to 28,000 establishments [2]—the sheer volume of choices adds to the challenge. 
<div style="float: right; width: auto; margin-left: 20px; margin-bottom: 20px;">
  <table style="font-size: 0.85em; border-collapse: collapse; font-family: sans-serif;">
    <thead>
      <tr>
        <th style="border: 1px solid #999; padding: 8px; background-color: #f3f3f3;">Borough</th>
        <th style="border: 1px solid #999; padding: 8px; background-color: #f3f3f3;">Mean rating</th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td style="border: 1px solid #999; padding: 8px;">Manhattan</td>
        <td style="border: 1px solid #999; padding: 8px;">4.29</td>
      </tr>
      <tr>
        <td style="border: 1px solid #999; padding: 8px;">Brooklyn</td>
        <td style="border: 1px solid #999; padding: 8px;">4.18</td>
      </tr>
      <tr>
        <td style="border: 1px solid #999; padding: 8px;">Queens</td>
        <td style="border: 1px solid #999; padding: 8px;">4.15</td>
      </tr>
      <tr>
        <td style="border: 1px solid #999; padding: 8px;">Bronx</td>
        <td style="border: 1px solid #999; padding: 8px;">3.93</td>
      </tr>
      <tr>
        <td style="border: 1px solid #999; padding: 8px;">Staten Island</td>
        <td style="border: 1px solid #999; padding: 8px;">3.96</td>
      </tr>
    </tbody>
    <caption style="caption-side: bottom; font-weight: bold; margin-bottom: 8px;">
      Table 1. Average TripAdvisor ratings by borough
    </caption>
  </table>
</div>
Tourists often turn to online reviews to guide their decisions, relying on platforms like Yelp, TripAdvisor or Google Maps. Drawing from TripAdvisor, restaurants across all five boroughs generally receive favorable ratings, all averaging around 4 out of 5 as seen in figure 1. You would think that a restaurant's state of sanitation would be somehow reflected in this rating, right?
<br><br>
No.  In fact customer ratings  correlate very poorly with the sanitary state of the individual restaurants. 
<br><br>
This article aims to serve as a guide for readers on where to eat, and one important aspect that is often overlooked in such guides is the health condition of the restaurant. Here, we seek to integrate the Health Department’s grading system with the more widely used customer review ratings in order to provide a more nuanced basis for making dining decisions.



<h2>New York City’s health inspections</h2> 

The Health Department scores the restaurants on an A, B, C scale where they represent how many sanitary violation points given. The grade represents sanitary violations like incorrect temperature on storage or evidence of rodents. [3]. Every restaurant is evaluated at least once a year and more if the restaurant receives a bad grade. In this article we work with restaurants evaluated in the two-year period 2022 to 2024. We combine this with review ratings of New York restaurants found on TripAdvisor. Each restaurant is rated on the scale from 1-5 with 5 being the best. In this article we have drawn data from 2004 to 2020.
<br><br>
Although these two datasets do not overlap in time, we consider the average rating over a span of 16 years to be a solid indicator of the restaurant’s general reputation and quality. Due to the limited availability of up-to-date and comprehensive review dataset, we have chosen to rely on this long-term average as a proxy for current customer sentiment and chosen to show up-to-date health inspection grades. It is important for readers to keep in mind that this approach is based on the best available data and should be interpreted with some consideration for the time gap between the datasets.
<br><br>
As illustrated in figure 1, there is little to no correlation between public ratings and official health grades. This disconnect likely stems from the differing criteria used by diners and inspectors. While health department evaluations focus solely on hygiene and safety—often invisible to the average customer—public reviews typically emphasize the more immediate, subjective aspects of the dining experience: food quality, flavor, service, ambiance, and value. A restaurant could offer a delicious meal in a cozy setting with attentive staff and still receive a low health grade due to back-of-house violations that most customers will never see. Conversely, a spotlessly clean establishment with bland food or poor service might earn an 'A' grade but still receive mediocre reviews. <br><br>
This contrast highlights the limitations of relying solely on either system. For tourists especially, understanding that a high customer rating doesn’t necessarily indicate cleanliness—and that a low health grade doesn’t always mean a bad meal—can help make more informed dining choices.

<figure style="text-align: center;">
  <img src="/assets/images/review_grade.png" style="max-width: 100%; height: auto;" alt="Review Grade Figure">
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;">
    Figure 1: billedtekst
  </figcaption>
</figure>


<h2> Restaurants information overview </h2> 
Manhattan clearly leads in restaurant count, boasting nearly 10,000 establishments, as seen in figure 2, ‘Restaurant counts’. This aligns with its role as a cultural and economic hub, drawing millions of tourists annually. Brooklyn and Queens offer slightly fewer restaurants but still maintain impressive numbers, representing the boroughs' rising culinary relevance. The Bronx and Staten Island have the fewest eateries, which may affect convenience for travelers staying in or venturing to those areas. For tourists aiming for the widest range of choices within walking distance, Manhattan remains the top pick. <br><br>
If we instead look at the plot ‘Most occurring cuisine’ in figure 2, the American cuisine dominates the city's culinary landscape, likely due to its versatility and ability to absorb multicultural influences. Chinese food and Coffee/Tea establishments rank closely behind, indicating a preference for quick, affordable dining options. Pizza, Mexican, Japanese, and Italian cuisines round out the top offerings, reflecting NYC's immigrant heritage and international appeal. Tourists looking for familiar or globally popular dishes will have no trouble satisfying their cravings in most boroughs. 
<br><br>
The health department inspects many different aspects, the most prevailing violations are shown in the plot ‘Violation codes’ in figure 2. Code 10F, for instance, which denotes ‘food not protected from contamination’, appears most frequently. Others like ‘sanitation infractions ‘(08A) and ‘plumbing issues’ (06D) are also common. These highlight operational lapses that could affect food safety, even in otherwise well-rated restaurants. Being aware of these recurring issues can help diners make informed decisions, especially when selecting lower-profile eateries.
<details style="margin: 20px 0;">
  <summary style="cursor: pointer; font-weight: bold; font-size: 1em;">
    Click to show most frequent health code violations
  </summary>
  <div style="display: flex; justify-content: center; margin-top: 10px;">
    <table style="font-size: 0.85em; border-collapse: collapse; font-family: sans-serif;">
      <caption style="caption-side: bottom; font-weight: bold; margin-bottom: 8px;">
        Table 2: Most frequent health code violations
      </caption>
      <thead>
        <tr>
          <th style="border: 1px solid #999; padding: 8px; background-color: #f3f3f3;">Code</th>
          <th style="border: 1px solid #999; padding: 8px; background-color: #f3f3f3;">Description</th>
        </tr>
      </thead>
      <tbody>
        <tr><td style="border: 1px solid #999; padding: 8px;">10F</td><td style="border: 1px solid #999; padding: 8px;">Non-food contact surface or equipment made of unacceptable material, not kept clean, or not properly sealed, raised, spaced or movable to allow accessibility for cleaning on all sides, above and underneath the unit.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">08A</td><td style="border: 1px solid #999; padding: 8px;">Establishment is not free of harborage or conditions conducive to rodents, insects or other pests.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">06D</td><td style="border: 1px solid #999; padding: 8px;">Food contact surface not properly washed, rinsed and sanitized after each use and following any activity when contamination may have occurred.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">02G</td><td style="border: 1px solid #999; padding: 8px;">Cold TCS food item held above 41 °F; smoked or processed fish held above 38 °F; intact raw eggs held above 45 °F; or reduced oxygen packaged (ROP) TCS foods held above required temperatures except during active necessary preparation.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">10B</td><td style="border: 1px solid #999; padding: 8px;">Anti-siphonage or back-flow prevention device not provided where required; equipment or floor not properly drained; sewage disposal system in disrepair or not functioning properly. Condensation or liquid waste improperly disposed of.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">04L</td><td style="border: 1px solid #999; padding: 8px;">Evidence of mice or live mice in establishment's food or non-food areas.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">06C</td><td style="border: 1px solid #999; padding: 8px;">Food, supplies, and equipment not protected from potential source of contamination during storage, preparation, transportation, display or service.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">02B</td><td style="border: 1px solid #999; padding: 8px;">Hot food item not held at or above 140° F.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">04N</td><td style="border: 1px solid #999; padding: 8px;">Filth flies or food/refuse/sewage associated with (FRSA) flies or other nuisance pests in establishment’s food and/or non-food areas. FRSA flies include house flies, blow flies, bottle flies, flesh flies, drain flies, Phorid flies and fruit flies.</td></tr>
        <tr><td style="border: 1px solid #999; padding: 8px;">04A</td><td style="border: 1px solid #999; padding: 8px;">Food Protection Certificate not held by supervisor of food operations.</td></tr>
      </tbody>
    </table>
  </div>
  </details>
Lastly in the plot 'Healt grade distribution' in figure 2 we observe the grades of the different boroughs. Only in Manhattan and barely Brooklyn do we see a higher proportion of A grades than B and C grades. This could be due to greater resources, tighter management, or perhaps more pressure to maintain reputational standards in the tourism-heavy boroughs. Staten Island, Bronx and Queens show larger amounts of grade B incidents. Queens have the largest amount of C grades indicating a lower focus on sanitation.
<figure style="text-align: center;">
  <iframe src="/assets/plots/barplots.html"
          style="width: 100%; max-width: 100%; height: 500px; border: none;">
  </iframe>
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;">
    Figure 2: MANGLER
  </figcaption>
</figure>



<h2>  When should you visit New York City?</h2> 
When viewing places to eat as a tourist visiting New York City, it is valuable to look at the distributions of health grades throughout the months of the year. In the polar plots in figure 3, the normalized distributions of health grades ‘A’ and ‘C’ are presented for each borough. Whether you want to look into the neighbourhood you’re staying in, or just get an overall feeling of the trends of the year, the clickable boxes on the right allow you to explore. Our data on Staten Island is unfortunately very limited, leaving us with a bit funky looking distributions due to very limited observations.
<br><br>
If we look at the better scoring restaurants with health grade A, there is a trend of higher rate of inspections with this grade in the spring months March, April and May. Meaning that if you wish to sort through restaurant knowing they recently got a good grade, the spring time is ideal for visiting the city. Whether the health grade reflects a higher sanitation focus within the restaurants, or the health department just is just more loose in the spring is up to you to interpret.
<br><br>
On the other hand if you are looking out for the non-ideal health grade  ‘C’, one could argue that the winter half year is a better time to visit. In this period there seems to be less health gradings of ‘C’ across all boroughs, suggesting that the cooler weather and perhaps less tourism reduces stress and makes room for better sanitation. On the other hand, the higher rates of ‘C’ gradings and warmer weather during the summertime is an indicator that some restaurants that do good in the winter, might perform worse in the summertime. <br><br>
With this one could argue that visiting New York City in the summer is the safer time, as restaurants with varying sanitation more often get flagged during this time.<br><br>
These visual patterns indicate that although violations are generally stable across time and space, tourists may want to pay extra attention during peak travel months (summer and holidays) and consider checking inspection histories.
<figure style="text-align: center; width: 100vw; margin-left: calc(-45vw + 50%);">
  <iframe src="/assets/plots/polarplots.html"
          style="width: 100%; height: 520px; border: none;">
  </iframe>
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;">
    Figure 3: MANGLER
  </figcaption>
</figure>


<h2> So where should I eat?</h2> 
If you're a tourist reading this article and wondering where to eat in New York City, Figure 4 can serve as a valuable guide to help you make an informed decision. The map provides a visual overview of restaurant scores across all five boroughs, allowing you to quickly identify high-scoring options based on your current location. Each dot on the map represents a single restaurant, with its score reflected through a color gradient—darker shades of green indicate lower violation scores corresponding to A grades, while more reddish tones suggest higher scores associated with C grades.
<br><br>
This intuitive visual format makes it easy to scan your surroundings and spot well-reviewed and hygienically sound eateries at a glance. By dragging your cursor over a dot, you can view detailed information including the restaurant's name, the type of cuisine it serves, its borough location, its health score and corresponding grade, and, if available, its review rating. The review rating is based on our compiled review dataset. In cases where the restaurant is part of a chain, and individual location data is unavailable, the rating shown represents an average of all locations of that chain within Manhattan.
<br><br>
Whether you're strolling through Manhattan, exploring the neighborhoods of Brooklyn, or venturing into the Bronx, Queens, or Staten Island, Figure 4 offers a practical, data-driven tool to support your culinary choices. So whether you're craving American food, looking for a cozy spot for coffee and tea, or feeling adventurous and curious to try Jamaican or Armenian cuisine, this map helps ensure a satisfying and informed dining experience during your visit to New York City.
<br><br>

<figure style="text-align: center;">
  <iframe src="/assets/plots/restaurant_map.html"
          style="width: 100%; max-width: 100%; height: 900px; border: none;" scrolling="no">
  </iframe>
  <figcaption style="font-style: italic; text-align: center; margin-top: 10px; color: #555;">
    Figure 4: MANGLER
  </figcaption>
</figure>

<b>References</b>: <br> 
[1]: https://www.contexttravel.com/stories/articles/36-hours-in-nyc?display_currency=USD <br>
[2]: https://oysterlink.com/spotlight/how-many-restaurants-does-nyc-have/?utm.com <br> 
[3]: https://a816-health.nyc.gov/ABCEatsRestaurants/#!/faq


</div>

<style>
  .content-wrapper {
    max-width: 1300px;
    margin: 0 auto;
    padding: 0 30px;
    box-sizing: border-box;
  }

  table {
    width: auto;
    max-width: 100%;
    margin-top: 1em;
  }
</style>