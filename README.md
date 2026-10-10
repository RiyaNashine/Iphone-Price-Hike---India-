# iPhone Price Hike Analysis (India, 2026)

Why did older iPhone models get **costlier** after the iPhone 18 Pro launch?

## Overview
On September 9, 2026, Apple launched the iPhone 18 Pro, 18 Pro Max and its first foldable, the iPhone Duo. Instead of making older models cheaper, as it usually does after a launch, Apple **raised prices** of the iPhone 16, 17, 17e and Air in India, and discontinued the iPhone 17 Pro and Pro Max.

This project measures how big these hikes were, which model was hit hardest, and what they suggest about Apple's pricing strategy. The reason cited for the hikes is rising memory chip and component costs across the smartphone industry.

## Price Changes (Sept 9, 2026)

| Model | Storage | Price Before | Price After | Increase (₹) | Increase (%) |
|---|---|---|---|---|---|
| iPhone 16 | 128 GB | ₹69,900 | ₹89,900 | ₹20,000 | 28.6% |
| iPhone 17 | 256 GB | ₹82,900 | ₹99,900 | ₹17,000 | 20.5% |
| iPhone 17 | 512 GB | ₹1,02,900 | ₹1,24,900 | ₹22,000 | 21.4% |
| iPhone 17e | 256 GB | ₹64,900 | ₹79,900 | ₹15,000 | 23.1% |
| iPhone 17e | 512 GB | ₹84,900 | ₹1,04,900 | ₹20,000 | 23.6% |
| iPhone Air | 256 GB | ₹1,19,900 | ₹1,49,900 | ₹30,000 | 25.0% |
| iPhone Air | 512 GB | ₹1,39,900 | ₹1,74,900 | ₹35,000 | 25.0% |

**Average increase: 23.9%**

## Key Insights
- Apple broke its usual post-launch pattern: every existing model got **more expensive**, by 20% to 29%, instead of being discounted.
- **Highest % hike:** iPhone 16 (128 GB) at 28.6%. **Highest ₹ hike:** iPhone Air 512 GB at ₹35,000.
- **Lowest % hike:** iPhone 17 (256 GB) at 20.5%.
- The iPhone Air saw a consistent ~25% hike on both storage variants.
- A 2-year-old iPhone 16 now costs almost ₹90,000, and even the cheapest model in the dataset (iPhone 17e, 256 GB) is ₹79,900, making the entry into the Apple ecosystem harder for budget buyers.
- Apple appears to be passing supply-chain cost pressure on to consumers rather than absorbing it.

## Charts
- **iPhone Price Hike: Before vs After**: old and new price side by side for each model
- **% Price Increase by Model**: percentage hike for each model
- ![Chart 1](Iphone%20price%20hike%20pngs/Screenshot%202026-10-10%20123112.png)
-![Chart 2](Iphone%20price%20hike%20pngs/Screenshot%202026-10-10%20123145.png)
-![Chart 3](Iphone%20price%20hike%20pngs/Screenshot%202026-10-10%20123159.png)
-![Chart 4](Iphone%20price%20hike%20pngs/Screenshot%202026-10-10%20123210.png)

## Approach
- **Data:** prices collected from news coverage (91mobiles, Free Press Journal, North Desk, Paid Free Droid), Apple India / GSMArena for official prices, and Wikipedia for price-change dates. The Excel file also has the iPhone 18 launch prices on a second sheet.
- **Calculations:** `₹ Increase = New Price − Old Price`, `% Increase = (₹ Increase / Old Price) × 100`
- **Tool:** Microsoft Excel
