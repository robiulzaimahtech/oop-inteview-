# oop-inteview-

#অবজেক্টভিত্তিক প্রোগ্রামিং (OOP)

অবজেক্টভিত্তিক প্রোগ্রামিং (OOP) হলো সফ্টওয়্যার ডেভেলপমেন্টের একটি পদ্ধতি, যেখানে প্রকৃত জগতের বস্তু এবং সেগুলোর মধ্যে সম্পর্কের অনুকরণ করে প্রোগ্রাম তৈরি করা হয়। এটি মূলত চারটি স্তম্ভের উপর ভিত্তি করে গড়ে উঠেছে:

১. ক্লাস (Class): একটি ক্লাস হলো কোডের একটি ব্লুপ্রিন্ট, যা একই ধরনের বস্তুর গঠন এবং আচরণ সংজ্ঞায়িত করে। এটি বস্তুর প্রপার্টি (ধর্ম) এবং মেথড (কার্য) নির্ধারণ করে। যেমন, একটি "গাড়ি" ক্লাসে গাড়ির রং, মডেল, গতি ইত্যাদি প্রপার্টি এবং চালু হওয়া, থামা, গতি বাড়ানো ইত্যাদি মেথড থাকতে পারে।

২. অবজেক্ট (Object): একটি অবজেক্ট হলো একটি ক্লাসের একটি নিদর্শন। এটি ক্লাসের সংজ্ঞায়িত প্রপার্টি এবং মেথডের একটি বিশেষ উদাহরণ। যেমন, একটি লাল রঙের, টয়োটা কোম্পানির ২০২৩ মডেলের "ক্যামরি" গাড়ি হলো "গাড়ি" ক্লাসের একটি অবজেক্ট।

৩. এনক্যাপুলেশন (Encapsulation): এনক্যাপুলেশন হলো ডেটা এবং এর সাথে সম্পর্কিত কার্যপ্রণালীকে একসাথে গুচ্ছ করে রাখার ধারণা। এটি কোডের বিভিন্ন অংশকে একে অপরের থেকে স্বাধীন করে এবং সিস্টেমের নিরাপত্তা বাড়ায়। যেমন, "গাড়ি" ক্লাসের ইঞ্জিনের অভ্যন্তরীণ কার্যকলাপকে গোপন রেখে শুধুমাত্র গাড়ি চালানোর মতো প্রয়োজনীয় কার্যপ্রণালীগুলিই বাইরে থেকে অ্যাক্সেসযোগ্য করা।

৪. ইনহেরিটেন্স (Inheritance): ইনহেরিটেন্স হলো একটি ক্লাসকে অন্য একটি ক্লাসের প্রপার্টি এবং মেথড "উত্তরাধিকার" সূত্রে পাওয়ার প্রক্রিয়া। এটি কোড পুনঃব্যবহারযোগ্যতা বাড়ায় এবং নতুন ক্লাস তৈরি করা সহজ করে তোলে। যেমন, একটি "ট্রাক" ক্লাস "গাড়ি" ক্লাস থেকে উত্তরাধিকারসূত্রে গাড়ির সব প্রপার্টি এবং মেথড পেতে পারে এবং সেগুলোর পাশাপাশি ট্রাকের নিজস্ব প্রপার্টি এবং মেথড (যেমন, বহন ক্ষমতা) যুক্ত করতে পারে।

উপরোক্ত চারটি স্তম্ভের মাধ্যমে OOP জটিল সফ্টওয়্যার সিস্টেমগুলিকে আরও সংগঠিত, বজায় রাখতে সহজ এবং দক্ষ করে তোলে।


অ্যাবস্ট্রাকশন (Abstraction) প্রোগ্রামিংয়ে কীভাবে কাজ করে:

অ্যাবস্ট্রাকশন হলো জটিলতাকে লুকিয়ে রেখে কেবলমাত্র প্রয়োজনীয় তথ্য ব্যবহার করে সমস্যা সমাধানের একটি কৌশল। প্রোগ্রামিংয়ে, এটি ব্যবহারকারীকে জটিল কার্যপ্রণালীগুলোর বিস্তারিত বিবরণ না জানিয়েই সেগুলো ব্যবহার করতে দেয়।

বাংলায় বলতে গেলে, অ্যাবস্ট্রাকশন হলো জিনিসকে সহজ করে উপস্থাপন করা। যেমন, আমরা গাড়ি চালানোর সময় ইঞ্জিন কীভাবে কাজ করে সে সম্পর্কে বিস্তারিত জানার দরকার নেই। আমরা শুধু স্টীয়ারিং চালিয়ে, গিয়ার পরিবর্তন করে এবং ব্রেক টিপে গাড়ি চালানোর মতো প্রয়োজনীয় কাজগুলোই করি।

এবার প্রোগ্রামিং এর কথায় ফিরে আসা যাক...

অ্যাবস্ট্রাকশনের ধরন:

Data Abstraction: এটি ডেটার গঠন এবং কার্যপ্রণালীকে লুকিয়ে রেখে শুধুমাত্র প্রয়োজনীয় তথ্য (যেমন, মান, প্রকার) প্রদর্শন করে।
Procedural Abstraction: এটি একটি জটিল কার্যপ্রণালীকে একটি ফাংশনে রূপান্তর করে, જેથી ব্যবহারকারীকে কেবল ফাংশনটি কীভাবে কাজ করে এবং কী ইনপুট দেওয়া প্রয়োজন সে সম্পর্কে জানতে হয়।
অ্যাবস্ট্রাকশনের সুবিধা:
কোড পুনঃব্যবহারযোগ্যতা: একই অ্যাবস্ট্রাক্ট ক্লাস বা ইন্টারফেস বিভিন্ন প্রোগ্রামে ব্যবহার করা যায়।
রক্ষণাবেক্ষণ সহজ: কোডের একটি অংশ পরিবর্তন করলেও অন্যান্য অংশগুলোকে প্রভাবিত না করেই কাজ চালিয়ে যেতে পারে।
দক্ষতা: জটিল বিবরণাদিকে না গিয়ে মূল কাজগুলোতে মনোযোগ দেওয়া যায়।
প্রোগ্রামিং ভাষায় অ্যাবস্ট্রাকশনের উদাহরণ:
Abstract Classes: এগুলো এমন ক্লাস যা সম্পূর্ণভাবে ব্যবহার করা যায় না কিন্তু অন্যান্য ক্লাস তৈরি করার জন্য টেমপ্লেট হিসাবে কাজ করে।
Interfaces: এগুলো ক্লাসের জন্য চুক্তিপত্রের মতো কাজ করে, ঠিক কী কী মেথড থাকতে হবে এবং সেগুলো কীভাবে কাজ করবে তা নির্ধারণ করে।





ইন্টারফেস প্রোগ্রামিংয়ে কীভাবে কাজ করে:
ইন্টারফেস হলো প্রোগ্রামিংয়ে একটি বিশেষ ধরনের অ্যাবস্ট্রাক্ট টাইপ যা ক্লাসের জন্য একটি চুক্তিপত্রের মতো কাজ করে। এটি নির্ধারণ করে যে কোন ক্লাস ইন্টারফেসটি ব্যবহার করতে চাইলে কী কী মেথড থাকতে হবে এবং সেগুলো কীভাবে কাজ করবে।

উদাহরণ:

Python
class Animal:
    def speak(self):
        raise NotImplementedError

class Dog(Animal):
    def speak(self):
        print("Woof!")

class Cat(Animal):
    def speak(self):
        print("Meow!")
Use code with caution. Learn more
এই উদাহরণে, Animal একটি ইন্টারফেস যা একটি speak() মেথড সংজ্ঞায়িত করে। Dog এবং Cat ক্লাস Animal ইন্টারফেস ব্যবহার করে এবং speak() মেথডকে নিজস্বভাবে বাস্তবায়ন করে।

ইন্টারফেস ব্যবহারের সুবিধা:

কোড পুনঃব্যবহারযোগ্যতা: একই ইন্টারফেস বিভিন্ন ক্লাসের জন্য ব্যবহার করা যায়।
Decoupling: ক্লাসগুলো একে অপরের উপর নির্ভরশীল নয়, কেবলমাত্র ইন্টারফেসের উপর নির্ভরশীল।
Polymorphism: বিভিন্ন ধরনের ক্লাস একই ইন্টারফেস ব্যবহার করে একইভাবে কাজ করতে পারে।
ইন্টারফেস ব্যবহারের উদাহরণ:

GUI টুলকিট: GUI টুলকিটগুলোতে বিভিন্ন ধরনের উইজেট (যেমন, বোতাম, টেক্সট বক্স) থাকে। প্রতিটি উইজেট একটি ইন্টারফেস বাস্তবায়ন করে যা নির্ধারণ করে যে উইজেটটি কীভাবে কাজ করবে।
Data Access Layer: ডাটা অ্যাক্সেস লেয়ার (DAL) ডাটাবেসের সাথে যোগাযোগের জন্য একটি ইন্টারফেস প্রদান করে। বিভিন্ন ধরনের ডাটাবেসের সাথে কাজ করার জন্য DAL-এর বিভিন্ন বাস্তবায়ন থাকতে পারে।
