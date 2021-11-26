# দ্বিতীয় অধ্যায় - টেক্সট এডিটর

## টেক্সট এডিটর

একজন সাধারন ব্যবহারকারী, যে কিনা একটু ইন্টারনেট ব্রাউজিং, একটু সিনেমা দেখা, গেম খেলার জন্যই শুধু কম্পিউটার ব্যবহার করে তারকাছে আসলেই টেক্সট এডিটর কোনো গুরুত্বপূর্ণ ব্যাপার না। কিন্তু আপনারা যারা এই টিউটোরিয়াল এতদিন ধরে পড়ছেন, তারা জানেন টেক্সটের গুরুত্ব। আমরা যা করেছি সব লিখেই করেছি। পুরো অপারেটিং সিস্টেম বহু বহু মানুষ লক্ষকোটি লাইন লিখে তৈরী করেছেন। গ্রাফিক্যাল জগতে আমরা gedit, kate উইন্ডোজ ব্যবহারকারীরা notepad এর সাথে পরিচিত। আমরা দেখেছি অনেক IDE\(Integrated Development Enviornment\) যার সাথে প্রোগ্রামিং ল্যাঙ্গুয়েজ স্পেসিফিক টেক্সট এডিটর থাকে। যেমন: Codeblocks বা SPE। মজার বিষয় হল আইডিইগুলো এতই জনপ্রিয় যে আমাদের সিএসই স্টুডেন্টরা অনেকে জানেনই না যে আইডিই ছাড়াও প্রোগ্রাম লিখে কম্পাইল করা যায়!

অনেক কারন আছে যার জন্য আপনি এই প্রাচীনপন্থী কমান্ডলাইন টেক্সট এডিটর শিখতে চাইবেন। এমন অবস্থায় পড়তে পারেন তা সার্ভারেই হোক বা আপনার নিজের কম্পিউটারে এমন কোনো সমস্যা যার জন্য গ্রাফিকাল এনভায়রনমেন্টে কাজ করতে পারছেন না, তখন এই টেক্সট এডিটরগুলোর একটি আপনাকে বাঁচাতে পারে। তাছাড়াও আপনার দক্ষতা এমন পর্যায়ে আপনি নিয়ে যেতেই পারেন যখন গ্রাফিকাল টেক্সট এডিটরের চেয়ে এগুলোই আপনার কাছে সুবিধাজনক মনে হবে।

আমরা এই অধ্যায়ে ৩টি টেক্সট এডিটরের সাথে পরিচিত হবো। ন্যানো\(Nano\), ভিম\(VIM\) এবং ইম্যাকস\(Emacs\)। ন্যানো একারনেই যে এটি খুবই সহজ, এবং এখনকার প্রায় সব ডিস্ট্রিবিউশনের সাথেই দেওয়া থাকে। এর বাংলা সাপোর্ট যথেষ্ট ভালো। VIM ঐতিহ্যগত কারনে। ইউনিক্স সিস্টেমে ভিম একটি বহুল ব্যবহৃত এডিটর। তবে এটিতে বাংলা লেখা যায় না। এটি খুবই ক্ষমতাধর এডিটর। আর ইম্যাকস হচ্ছে ভিমের সবচেয়ে বড় প্রতিদ্বন্দ্বী। তুলনামূলক সহজ। প্রচুর অপশন ও ব্যবহারযোগ্যতা এবং বাংলা সাপোর্ট আছে।

আমি প্রত্যেকটিতেই বাংলা সাপোর্ট সম্পর্কে বলেছি তবে আপনার টার্মিনাল ইমুলেটরের বাংলা সাপোর্ট ভালো না হলে কোনোটাতেই বাংলা লিখতে পারবেন না ঠিকভাবে। এ পর্যন্ত আমি konsole এবং ড্রপডাউন টার্মিনাল yakuake এ ঠিকঠাক বাংলা সাপোর্ট পেয়েছি। আপনারা এই দুটি ইন্সটল করে নিতে পারেন।

আপনাকে তিনটেই শিখতে হবে এমন না। আপনি চাইলে শুধু ন্যানোই যথেষ্ট আবার তার সাথে ভিম ও ইম্যাকস এর একটি শিখতে পারেন। আবার চাইলে তিনটিই।

* [**ন্যানো**:](3.2.1.0.nano/) ন্যানো এর ব্যবহার।
  * [**ন্যানোর প্রাথমিক ব্যবহার**:](3.2.1.0.nano/3.2.1.1.nano-basic.md) ন্যানো এডিটরের প্রাথমিক ব্যবহার।
  * [**ন্যানো - এডিটিং এবং নেভিগেশন**:](3.2.1.0.nano/3.2.1.2.nano-editnavigate.md) এডিটিং, সার্চ এবং রিপ্লেস এবং নেভিগেশন।
  * [**ন্যানো কনফিগারেশন**:](3.2.1.0.nano/3.2.1.3.nano-configuration.md) ন্যানো কনফিগার করা।
* [**ভিম**:](3.2.2.0.vim/) ভিম এর ব্যবহার।
  * [**ভিমের এডিটিং মোড**:](3.2.2.0.vim/3.2.2.1.vim-editing-mode.md) ভিমের মোড সম্পর্কিত ধারণা।
  * [**ভিম-এর বেসিক এডিটিং**:](3.2.2.0.vim/3.2.2.2.vim-basic-editing.md) ভিম-এর বেসিক এডিটিং।
  * [**ভিম: সার্চ এ্যান্ড রিপ্লেস**:](3.2.2.0.vim/3.2.2.3.vim-search-and-replace.md) ভিমে সার্চ এবং রিপ্লেস অপারেশন।
  * [**ভিম: একাধিক ফাইল নিয়ে কাজ করা**:](3.2.2.0.vim/3.2.2.4.vim-editing-multiple-files.md) ভিমে একাধিক ফাইল নিয়ে কাজ করা।
* [**ইম্যাকস্**:](3.2.3.0.emacs/) ইম্যাকস্ এর ব্যবহার।
  * [**ইম্যাকস্: প্রথম ধাপ**:](3.2.3.0.emacs/3.2.3.1.emacs-first-step.md) ইম্যাকস্ চালু, ইন্টারফেস পরিচিতি ও বন্ধ।
  * [**ইম্যাকস্: ক্যারেক্টার, কী এবং কমান্ড**:](3.2.3.0.emacs/3.2.3.2.emacs-keys-and-command.md) ক্যারেক্টার, কী এবং কমান্ড সম্পর্কিত আলোচনা।
  * [**ইম্যাকস্: বেসিক এডিটিং**:](3.2.3.0.emacs/3.2.3.3.emacs-basic-editing.md) ইম্যাকসে বেসিক এডিটিং।
  * [**ইম্যাকস্: সার্চ এ্যান্ড রিপ্লেস**:](3.2.3.0.emacs/3.2.3.4.emacs-search-and-replace.md) ইম্যাকসে সার্চ এবং রিপ্লেস।
  * [**ইম্যাকস্: একাধিক ফাইল এডিট করা**:](3.2.3.0.emacs/3.2.3.5.emacs-editing-multiple-files.md) ইম্যাকসে একাধিক ফাইল নিয়ে কাজ করা।
