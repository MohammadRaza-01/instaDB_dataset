# instaDB_dataset

```
use instagramDB

db.users.insertMany([
  {
    username: "arjun_dev",
    fullName: "Arjun Sharma",
    age: 22,
    email: "arjun@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Pune",
    interests: ["coding", "technology", "travel"],
    stats: {
      followers: 12500,
      following: 850,
      posts: 145
    },
    joinedAt: ISODate("2022-06-15")
  },

  {
    username: "priya_travels",
    fullName: "Priya Patil",
    age: 25,
    email: "priya@gmail.com",
    accountType: "creator",
    isVerified: true,
    isPrivate: false,
    city: "Mumbai",
    interests: ["travel", "photography", "food"],
    stats: {
      followers: 245000,
      following: 1200,
      posts: 620
    },
    joinedAt: ISODate("2020-04-11")
  },

  {
    username: "rahul_fitness",
    fullName: "Rahul Verma",
    age: 28,
    email: "rahul@gmail.com",
    accountType: "business",
    isVerified: false,
    isPrivate: false,
    city: "Delhi",
    interests: ["fitness", "gym", "health"],
    stats: {
      followers: 45200,
      following: 900,
      posts: 380
    },
    joinedAt: ISODate("2021-01-22")
  },

  {
    username: "sneha_art",
    fullName: "Sneha Kulkarni",
    age: 21,
    email: "sneha@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: true,
    city: "Pune",
    interests: ["art", "design", "illustration"],
    stats: {
      followers: 8200,
      following: 650,
      posts: 210
    },
    joinedAt: ISODate("2023-02-14")
  },

  {
    username: "rohan_codes",
    fullName: "Rohan Joshi",
    age: 23,
    email: "rohan@gmail.com",
    accountType: "personal",
    isVerified: false,
    isPrivate: false,
    city: "Bengaluru",
    interests: ["coding", "javascript", "react"],
    stats: {
      followers: 9800,
      following: 1100,
      posts: 98
    },
    joinedAt: ISODate("2022-09-09")
  },

  {
    username: "anjali_foodie",
    fullName: "Anjali Mehta",
    age: 26,
    email: "anjali@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Mumbai",
    interests: ["food", "travel", "lifestyle"],
    stats: {
      followers: 67300,
      following: 780,
      posts: 450
    },
    joinedAt: ISODate("2021-05-16")
  },

  {
    username: "sameer_photo",
    fullName: "Sameer Khan",
    age: 29,
    email: "sameer@gmail.com",
    accountType: "creator",
    isVerified: true,
    isPrivate: false,
    city: "Hyderabad",
    interests: ["photography", "travel", "nature"],
    stats: {
      followers: 310000,
      following: 1450,
      posts: 890
    },
    joinedAt: ISODate("2019-10-01")
  },

  {
    username: "neha_music",
    fullName: "Neha Deshmukh",
    age: 27,
    email: "neha@gmail.com",
    accountType: "creator",
    isVerified: true,
    isPrivate: false,
    city: "Pune",
    interests: ["music", "singing", "dance"],
    stats: {
      followers: 185000,
      following: 500,
      posts: 340
    },
    joinedAt: ISODate("2020-08-25")
  },

  {
    username: "vijay_business",
    fullName: "Vijay Shah",
    age: 35,
    email: "vijay@gmail.com",
    accountType: "business",
    isVerified: true,
    isPrivate: false,
    city: "Ahmedabad",
    interests: ["business", "startup", "technology"],
    stats: {
      followers: 92000,
      following: 1300,
      posts: 275
    },
    joinedAt: ISODate("2018-03-12")
  },

  {
    username: "aditya_gamer",
    fullName: "Aditya Singh",
    age: 24,
    email: "aditya@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Noida",
    interests: ["gaming", "technology", "esports"],
    stats: {
      followers: 78500,
      following: 720,
      posts: 520
    },
    joinedAt: ISODate("2021-11-19")
  },

  {
    username: "pooja_fashion",
    fullName: "Pooja Rao",
    age: 27,
    email: "pooja@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Bengaluru",
    interests: ["fashion", "beauty", "lifestyle"],
    stats: {
      followers: 112000,
      following: 890,
      posts: 410
    },
    joinedAt: ISODate("2020-12-10")
  },

  {
    username: "manish_travel",
    fullName: "Manish Yadav",
    age: 30,
    email: "manish@gmail.com",
    accountType: "personal",
    isVerified: false,
    isPrivate: false,
    city: "Jaipur",
    interests: ["travel", "adventure", "photography"],
    stats: {
      followers: 15600,
      following: 2100,
      posts: 189
    },
    joinedAt: ISODate("2022-01-05")
  },

  {
    username: "kavya_writer",
    fullName: "Kavya Nair",
    age: 26,
    email: "kavya@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: true,
    city: "Kochi",
    interests: ["writing", "books", "poetry"],
    stats: {
      followers: 9300,
      following: 540,
      posts: 275
    },
    joinedAt: ISODate("2019-07-17")
  },

  {
    username: "amit_ai",
    fullName: "Amit Gupta",
    age: 24,
    email: "amit@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Pune",
    interests: ["ai", "machine learning", "python"],
    stats: {
      followers: 27600,
      following: 730,
      posts: 132
    },
    joinedAt: ISODate("2023-01-19")
  },

  {
    username: "simran_dance",
    fullName: "Simran Kaur",
    age: 23,
    email: "simran@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Chandigarh",
    interests: ["dance", "music", "fitness"],
    stats: {
      followers: 134000,
      following: 460,
      posts: 350
    },
    joinedAt: ISODate("2021-04-07")
  },

  {
    username: "farhan_design",
    fullName: "Farhan Ahmed",
    age: 28,
    email: "farhan@gmail.com",
    accountType: "personal",
    isVerified: false,
    isPrivate: false,
    city: "Hyderabad",
    interests: ["design", "uiux", "technology"],
    stats: {
      followers: 7400,
      following: 680,
      posts: 160
    },
    joinedAt: ISODate("2022-02-22")
  },

  {
    username: "riya_makeup",
    fullName: "Riya Kapoor",
    age: 31,
    email: "riya@gmail.com",
    accountType: "business",
    isVerified: false,
    isPrivate: false,
    city: "Mumbai",
    interests: ["beauty", "makeup", "fashion"],
    stats: {
      followers: 98500,
      following: 620,
      posts: 540
    },
    joinedAt: ISODate("2018-11-13")
  },

  {
    username: "nikhil_startup",
    fullName: "Nikhil Jain",
    age: 34,
    email: "nikhil@gmail.com",
    accountType: "business",
    isVerified: true,
    isPrivate: false,
    city: "Gurugram",
    interests: ["startup", "business", "saas"],
    stats: {
      followers: 156000,
      following: 970,
      posts: 290
    },
    joinedAt: ISODate("2017-05-08")
  },

  {
    username: "deepak_cricket",
    fullName: "Deepak Thakur",
    age: 25,
    email: "deepak@gmail.com",
    accountType: "personal",
    isVerified: false,
    isPrivate: false,
    city: "Nagpur",
    interests: ["cricket", "sports", "fitness"],
    stats: {
      followers: 18900,
      following: 920,
      posts: 220
    },
    joinedAt: ISODate("2021-08-30")
  },

  {
    username: "isha_nature",
    fullName: "Isha Roy",
    age: 29,
    email: "isha@gmail.com",
    accountType: "creator",
    isVerified: false,
    isPrivate: false,
    city: "Kolkata",
    interests: ["nature", "wildlife", "photography"],
    stats: {
      followers: 38900,
      following: 1500,
      posts: 320
    },
    joinedAt: ISODate("2020-02-02")
  }
])

```
