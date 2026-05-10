// ============================================
// CUSTOMIZATION EXAMPLES
// ============================================

/* 
   This file shows EXACTLY how to customize the gallery data.
   Copy the format and replace with your own content!
*/

// ============================================
// EXAMPLE 1: SIMPLE CUSTOMIZATION
// ============================================

// ORIGINAL (In script.js):
/*
const galleryData = {
    memories: {
        name: 'Memories',
        emoji: '📸',
        video: 'videos/memories.mp4',
        videoTitle: 'Our Beautiful Memories',
        videoDescription: 'A collection of moments that define us.',
        items: [
            { id: 1, src: 'images/memory-1.jpg', title: 'First Meeting', date: 'Day 1' },
            // ... more items
        ]
    }
}
*/

// YOUR CUSTOMIZATION:
const customGalleryData = {
    memories: {
        name: 'Our Photos',                    // 👈 Changed name
        emoji: '🥰',                           // 👈 Changed emoji
        video: 'videos/memories.mp4',
        videoTitle: 'Our Amazing Journey',     // 👈 Changed title
        videoDescription: 'These are the moments that made us smile.', // 👈 Changed description
        items: [
            { id: 1, src: 'images/memory-1.jpg', title: 'The Day We Met', date: 'November 15' },
            { id: 2, src: 'images/memory-2.jpg', title: 'First Coffee Date', date: 'November 20' },
            { id: 3, src: 'images/memory-3.jpg', title: 'Dancing in Your Room', date: 'December 1' },
            { id: 4, src: 'images/memory-4.jpg', title: 'Rainy Day Cuddles', date: 'December 15' },
            { id: 5, src: 'images/memory-5.jpg', title: 'Sunset at the Park', date: 'January 10' },
            { id: 6, src: 'images/memory-6.jpg', title: 'New Year Kiss', date: 'January 1' },
        ]
    }
};

// ============================================
// EXAMPLE 2: ALL THREE PROFILES CUSTOMIZED
// ============================================

const fullCustomization = {
    memories: {
        name: '📸 Our Photos',
        emoji: '📸',
        video: 'videos/memories.mp4',
        videoTitle: 'Treasured Memories',
        videoDescription: 'Every moment with you is a memory I cherish forever.',
        items: [
            { id: 1, src: 'images/memory-1.jpg', title: 'First Day Together', date: 'June 1st' },
            { id: 2, src: 'images/memory-2.jpg', title: 'Your Beautiful Smile', date: 'June 5th' },
            { id: 3, src: 'images/memory-3.jpg', title: 'Cozy Movie Night', date: 'June 12th' },
            { id: 4, src: 'images/memory-4.jpg', title: 'Adventure Time!', date: 'June 20th' },
            { id: 5, src: 'images/memory-5.jpg', title: 'Sleeping Beauty', date: 'June 25th' },
            { id: 6, src: 'images/memory-6.jpg', title: 'Us Against The World', date: 'July 1st' },
        ]
    },
    moments: {
        name: '💞 Precious Moments',
        emoji: '💞',
        video: 'videos/moments.mp4',
        videoTitle: 'Every Second Counts',
        videoDescription: 'These are the small moments that mean everything.',
        items: [
            { id: 1, src: 'images/moment-1.jpg', title: 'Your Laugh', date: 'Today' },
            { id: 2, src: 'images/moment-2.jpg', title: 'Holding Hands', date: 'Yesterday' },
            { id: 3, src: 'images/moment-3.jpg', title: 'Morning Cuddles', date: 'Last Week' },
            { id: 4, src: 'images/moment-4.jpg', title: 'Stargazing Together', date: '2 Weeks Ago' },
            { id: 5, src: 'images/moment-5.jpg', title: 'Secret Hugs', date: '3 Weeks Ago' },
            { id: 6, src: 'images/moment-6.jpg', title: 'Sunset Romance', date: 'Last Month' },
        ]
    },
    adventures: {
        name: '✨ Our Adventures',
        emoji: '✨',
        video: 'videos/adventures.mp4',
        videoTitle: 'Exploring Together',
        videoDescription: 'Every journey with you is an adventure I never want to end.',
        items: [
            { id: 1, src: 'images/adventure-1.jpg', title: 'Mountain Peak Victory', date: 'Summer Vacation' },
            { id: 2, src: 'images/adventure-2.jpg', title: 'Beach Day Fun', date: 'June Holiday' },
            { id: 3, src: 'images/adventure-3.jpg', title: 'City Exploration', date: 'Last Month' },
            { id: 4, src: 'images/adventure-4.jpg', title: 'Forest Hike', date: '2 Months Ago' },
            { id: 5, src: 'images/adventure-5.jpg', title: 'Camping Trip', date: 'Spring Break' },
            { id: 6, src: 'images/adventure-6.jpg', title: 'Road Trip Vibes', date: 'Winter Holiday' },
        ]
    }
};

// ============================================
// EXAMPLE 3: DIFFERENT PROFILE NAMES
// ============================================

const alternativeProfiles = {
    memories: {
        name: 'All Our Love',              // Alternative name
        emoji: '❤️',
        // ... rest stays same
    },
    moments: {
        name: 'Tiny Perfect Moments',      // Alternative name
        emoji: '💫',
        // ... rest stays same
    },
    adventures: {
        name: 'Wild & Free',               // Alternative name
        emoji: '🚀',
        // ... rest stays same
    }
};

// ============================================
// EXAMPLE 4: ROMANTIC EMOJI COMBINATIONS
// ============================================

const emojiOptions = {
    profile1: '❤️',   // Classic red heart
    profile2: '💕',   // Two hearts
    profile3: '💑',   // Couple with hearts
    profile4: '👫',   // Couple
    profile5: '💕',   // Pink hearts
    profile6: '✨',   // Sparkles
    profile7: '🌹',   // Rose
    profile8: '💐',   // Bouquet
    profile9: '🎀',   // Bow
    profile10: '💎',  // Diamond
};

// ============================================
// EXAMPLE 5: CUTE TITLES IDEAS
// ============================================

const cuteTitleIdeas = {
    // For photos together
    together: [
        'Us',
        'My Favorite',
        'Us Time',
        'Together Forever',
        'Perfect Moment',
        'Us & The World',
        'My Love',
        'Your Love',
        'Our Story',
        'You & Me',
        'Dreams With You',
    ],
    
    // For photos of her
    ofHer: [
        'Your Smile',
        'Beautiful You',
        'Your Laugh',
        'Angel Face',
        'Mesmerized',
        'Goddess',
        'Queen',
        'My World',
        'Everything',
        'Your Beauty',
        'Stunning',
    ],
    
    // For special moments
    special: [
        'First Kiss',
        'First Date',
        'Our Anniversary',
        'Best Day Ever',
        'I Love You',
        'Forever Starts Now',
        'Finally Home',
        'My Happy Place',
        'Happily Ever After',
        'The One',
        'Soulmate',
    ],
    
    // For adventures
    adventures: [
        'Exploring',
        'New Adventures',
        'Road Trip',
        'Wanderlust',
        'Travel Buddies',
        'Wild & Free',
        'Making Memories',
        'Adventure Awaits',
        'Bucket List',
        'Somewhere Over',
        'Passport Ready',
    ]
};

// ============================================
// EXAMPLE 6: DATE FORMAT IDEAS
// ============================================

const dateFormatExamples = {
    // Option 1: Simple numbers
    option1: 'Day 1',
    option2: 'Day 2',
    option3: 'Week 1',
    
    // Option 2: Full dates
    option4: 'June 15, 2024',
    option5: 'July 20, 2024',
    
    // Option 3: Relative dates
    option6: 'Today',
    option7: 'Yesterday',
    option8: 'Last Week',
    option9: '2 Weeks Ago',
    
    // Option 4: Seasonal
    option10: 'Summer Vibes',
    option11: 'Winter Holiday',
    option12: 'Spring Break',
    
    // Option 5: Anniversary based
    option13: '1st Month',
    option14: '3rd Month',
    option15: '1 Year Together',
    
    // Option 6: Story based
    option16: 'The Beginning',
    option17: 'The First Kiss',
    option18: 'Forever Starts Here',
};

// ============================================
// EXAMPLE 7: COLOR CUSTOMIZATION
// ============================================

const colorThemes = {
    romantic: {
        '--primary-color': '#e50914',      // Netflix red
        '--accent-pink': '#ff69b4',        // Hot pink
        '--accent-gold': '#ffd700',        // Gold
    },
    purpleLove: {
        '--primary-color': '#6f2da8',      // Deep purple
        '--accent-pink': '#c448d1',        // Orchid
        '--accent-gold': '#e6b3ff',        // Lavender
    },
    oceanBlue: {
        '--primary-color': '#0066cc',      // Ocean blue
        '--accent-pink': '#00ccff',        // Cyan
        '--accent-gold': '#ffcc00',        // Sunlight
    },
    sunsetGlow: {
        '--primary-color': '#ff6b35',      // Coral
        '--accent-pink': '#ff8c42',        // Orange
        '--accent-gold': '#ffd93d',        // Golden yellow
    },
    mintChocolate: {
        '--primary-color': '#1a9b3e',      // Mint green
        '--accent-pink': '#ff69b4',        // Pink
        '--accent-gold': '#fff9c4',        // Pale yellow
    },
    blackRose: {
        '--primary-color': '#8b0000',      // Dark red
        '--accent-pink': '#ff1493',        // Deep pink
        '--accent-gold': '#daa520',        // Goldenrod
    }
};

// ============================================
// HOW TO USE THESE EXAMPLES
// ============================================

/*
1. Copy the customization you like
2. Open script.js
3. Find: const galleryData = {
4. Replace the entire galleryData object with your version
5. Save the file
6. Refresh your browser

IMPORTANT: Keep the structure exactly the same!
Only change the VALUES, not the KEYS.

Right:  name: 'My Custom Name'  ✅
Wrong:  myCustomName: 'Name'    ❌

Right:  { id: 1, src: 'path', title: 'name', date: 'when' }  ✅
Wrong:  { imgId: 1, image: 'path', ... }                     ❌
*/

// ============================================
// VALIDATION CHECKLIST
// ============================================

// Before using your customization, check:
const validationChecklist = [
    // ❌ Did I keep the exact structure?
    // ❌ Did I use proper JSON syntax?
    // ❌ Did I close all brackets { } and [ ]?
    // ❌ Did I close all quotes ' or "?
    // ❌ Did I add commas between items?
    // ❌ Did I NOT add a comma after the last item?
    // ❌ Did I match the file paths exactly?
    // ❌ Did I test it in the browser?
];

// ============================================
// SYNTAX TIPS
// ============================================

/*
Correct Syntax Examples:

// ✅ CORRECT
const data = {
    name: 'Hello',
    items: [
        { id: 1, title: 'First' },
        { id: 2, title: 'Second' }
    ]
};

// ❌ WRONG - Missing comma after 'Hello'
const data = {
    name: 'Hello'
    items: [...]
};

// ❌ WRONG - Comma after last item
const data = {
    items: [
        { id: 1, title: 'First' },
    ]  // ← This comma shouldn't be here
};

// ❌ WRONG - Missing quotes around keys
const data = {
    name: Hello,  // Should be 'Hello' or "Hello"
};

// ✅ CORRECT - Numbers don't need quotes
const data = {
    id: 1,
    count: 5
};
*/

// ============================================
// COMMON MISTAKES & FIXES
// ============================================

const mistakes = {
    mistake1: {
        problem: "Copy-pasting creates weird characters",
        solution: "Type manually or use Notepad, not Word"
    },
    mistake2: {
        problem: "Files paths have wrong slashes",
        solution: "Use forward slashes: images/photo.jpg (not backslash)"
    },
    mistake3: {
        problem: "Image titles have apostrophes that break code",
        solution: "Use: I\'m or \"I'm\" or use single quotes \"I'm\""
    },
    mistake4: {
        problem: "Videos not playing",
        solution: "Must be .mp4 format, not .mov or .avi"
    },
    mistake5: {
        problem: "Symbols like é, ñ, 中 don't display",
        solution: "Use plain English or save file as UTF-8"
    }
};

// ============================================
// READY TO START?
// ============================================

/*
You've got this! 💪

1. Pick one of the examples above
2. Customize with your own content
3. Save the file
4. Test in your browser
5. Deploy to Vercel/Netlify

Questions? Check the README.md file for detailed help!
*/
