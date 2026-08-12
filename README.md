# 💬 LinkedIn Post Comments Scraper

Extract every person who commented on any LinkedIn post, enriched with full profile data. Paste the post URL and get a clean, structured export of the whole commenter list with headline, location, follower count, work history, education, and skills attached to each row.

Commenters are the highest-intent segment of any post's audience. **Perfect for:**
- Warm outbound list building
- Competitor audience mining
- Launch and event follow-ups
- Social intent signal collection

> No login cookies required.

---

## ⚙️ How It Works

| Step | What Happens |
|------|-------------|
| **Input** | Submit one or more LinkedIn post URLs |
| **Collection** | Actor pulls the full list of commenters on the post |
| **Enrichment** | Each commenter is enriched with full profile-level data |
| **Output** | Clean JSON / CSV / Excel export |

---

## 📌 Data Fields

| Field | Description |
|-------|-------------|
| `publicIdentifier` | Public LinkedIn profile slug |
| `linkedInIdentifier` | LinkedIn's internal profile identifier |
| `memberIdentifier` | Numeric LinkedIn member ID |
| `linkedInUrl` | Direct profile URL |
| `firstName` | First name |
| `lastName` | Last name |
| `headline` | Profile headline |
| `summary` | Profile about/summary section |
| `location` | Profile location |
| `followerCount` | Total followers |
| `premium` | Whether the member has LinkedIn Premium |
| `is_open_profile` | Whether the profile is an Open Profile |
| `is_creator` | Whether creator mode is enabled |
| `is_influencer` | Whether the member is a LinkedIn Influencer |
| `is_self` | Internal flag for the requesting account |
| `is_relationship` | Whether the member is a connection |
| `websites` | Websites listed on the profile |
| `connections_count` | Total connections |
| `birthdate` | Birthdate, if public |
| `positions` | Full work history (company, title, dates, description, company ID, LinkedIn URL, logo) |
| `schools` | Full education history (school, degree, grade, dates, school ID) |
| `skills` | Listed skills with endorsement counts and insights |
| `languages` | Languages listed on the profile |
| `recommendations` | Recommendations received |
| `volunteering_experience` | Volunteering history |
| `photoUrl` | Profile picture URL |
| `backgroundUrl` | Profile banner image URL |
| `request_type` | Type of request run |
| `reaction` | `TRUE` if the person also reacted to the post |
| `reaction_type` | Reaction type if any: `LIKE`, `APPRECIATION`, `INTEREST`, `PRAISE`, `EMPATHY`, `ENTERTAINMENT` |
| `comment` | `TRUE` for everyone in this export |

---

## 📊 Sample Output

```json
{
  "publicIdentifier": "sai-kalyan7",
  "linkedInIdentifier": "ACoAACTy83wBFbRBk5OzcOHsvFheAwQWHG0diGE",
  "memberIdentifier": "619901820",
  "linkedInUrl": "https://www.linkedin.com/in/sai-kalyan7",
  "firstName": "Melimi Sai Kalyan",
  "lastName": "Chakravarthy",
  "headline": "AI/ machine learning developer python",
  "location": "Hyderabad, Telangana, India",
  "followerCount": "566",
  "premium": "FALSE",
  "is_open_profile": "FALSE",
  "is_creator": "FALSE",
  "positions": {
    "positionsCount": 4,
    "positionHistory": [
      {
        "start": null,
        "end": null,
        "company": "Microsoft",
        "position": "Software Engineer",
        "company_id": "1035",
        "skills": []
      }
    ]
  },
  "schools": {
    "educationsCount": 0,
    "educationHistory": []
  },
  "skills": {
    "Skills": [
      { "name": "Analytical Skills", "endorsement_count": 0 },
      { "name": "REST APIs", "endorsement_count": 0 }
    ]
  },
  "request_type": "Social Enrichment",
  "reaction": "FALSE",
  "reaction_type": "",
  "comment": "TRUE"
}
```

---

## 💰 Pricing

**$5.00 per 1,000 commenters**

One flat rate. Full profile enrichment is included by default with no add-on tiers.

---

## 📦 Estimated Delivery Time

| Volume | Delivery Time |
|--------|--------------|
| Up to 10,000 commenters | Within 3 hours |
| 10,000 to 50,000 commenters | 3 to 6 hours |
| 50,000+ commenters | 6 to 12 hours |

---

## 📁 How to Use

1. [Create a free Apify account](https://apify.com)
2. Open this actor and paste your LinkedIn post URL as input
3. Run the actor
4. Download your structured JSON, CSV, or Excel output

---

## ⚠️ Disclaimer

This actor is intended for legitimate business use cases such as market research, lead generation, and outreach. Use it in compliance with LinkedIn's Terms of Service and applicable data privacy regulations (GDPR, CCPA, etc.). The actor does not require or store any LinkedIn credentials.
