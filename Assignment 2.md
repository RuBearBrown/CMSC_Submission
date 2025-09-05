# Assignment 2: It's all numbers.

If I understand correctly Sir, the Assignment asks for a proposal of either another type of data being Represented by numbers, or another way a data gets represented with numbers. I will answer both either way because I do not have enough time that question.

1. Another Type of Data being represented:

I have though of a new type of data format (or atleast a type of Data Format that if exists a real world counterpart, I am just not aware of) specifically designed for AI Language Models, especially for "Companion" type Models in which, certain informations must be remembered to continue the context of a conversation.

As you have discussed sir, certain data requires more complex ways of storage than just the simple Hexadecimal or RGB format for Colors or Unicode for Characters. An example that you have given sir, is Music, in which Melodies, Instrument type, Tempo and Sound Duration are all stored in their own ways.

With this in mind, I propose a Special "Memory File" format that LLMs can use to store specific information that can be relevant for "Context Continuity" or to simulate a "Persistent Memory". Firt of, like in Music, multiple distinct "elements" must be identifies to know what the data really contains, such as the "Pitch", "Tone" etc. So for this data file, these data should be stored:

a. Information Type - I propose that this can only be a limited group of keywords (just like as "int, char, bool, string, double, float") used to identify what "information" these memories will contain. These can include:
"Event" - To signal that the memory file will contain multiple strings of discriptive texts recalling an Event.
"Information" - To signal that the memory file will contain non-event type information but might still be discriptive such as Baking Instructions, Directions to a certain place or other similar information. 
"User Characteristic" - To signal that the memory file will contain Important key words that describes the user, may it be certain characteristics, dislikes or similar informations.
"Agent Characteristic" - Similar to User Characteristic but is used by the AI to keep take records of their own "Identity" and to keep it consistent.

b. Sub Category - This is another piece of data that aides in further classifying the "Information Type" and it's possible contents. It varies depending ong the Inforamtion type such as "Place Name", "Weather Type" or "Activities" for "Event" type Information, "Name", "Age", "Gender" and such for User Characteristics, "Instruction", "Trivia", or "Rule" for "Information" type information and such, just so the AI or the Program can more easily know what category the data is supposed to be for.

c. Date and Time - This is an optional piece of data that I propose that can be useful for the LLM to gain context and simulate more "immersion" for the user, specially when trying to recall "old memories" or to have a concept for the passing of time which might be helpful somewhere in the conversation.

d. Summary - This is a short summary of the content of the Data, it might purely be keywords and tags, this is so that the LLM can retreive the important information a lot quicker instead of having to find the data in the more detailed recollection.

e. Expanded Data - This is the somewhat "Raw" version of the data, which contains a detailed recollection of an event, a more specific preference of a user or others like that, this can be used by the LLM to "remember" the context of that specific "Memory".

This string of pure data will be stored in a single file, probably in the binary version of the plain text in a unicode or ascii format or a more efficient way, that requires a decoder for the LLM to actually recognize which data is useful and which section of the data is important for them based on their case.

2. Another way to Represent Data

Now, since Number Values for the amount of Red, Green and Blue is used to represent a range of colors in a very efficient manner, I will probably propose an Inefficient way to represent colors instead.

One idea would be to instead break a the color spectrum into a Cartesian plane instead, where each colors are just represented by two numbers, the X and the Y values and a decoder will try to reconstruct those values by referring to the Cartesian plane that contains the colors. This means that there are a vastly smaller amount of colors to choose from but it should theoretically reduce the amount of data to be stored right?

This idea came up when I remembered a YouTube video about "Rare Team Fortress Two Cosmetic Colors" where the cosmetic colors are randomly chosen from a Rainbow looking Color Pallete using the X and Y coordinates. The rarest of which is a small 20x20 pixel wide box of the color White that appears in the middle of the Color Pallete, meaning it is a very rare thing to get.

I found the Video that I mentioned: (https://www.youtube.com/watch?v=ydQ6FbpFSjk)




