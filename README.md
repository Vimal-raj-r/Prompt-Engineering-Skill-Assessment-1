# 19TD608-Prompt-Engineering
# Skill-Assessment-1
### VIMALRAJ R
### 212223040242
# AIM:
To experiment with different prompts and strategies to  adjust the model's responses and explore ways to improve its performance in complex reasoning or creative tasks.

# PROMPTS:
### 1. Translation:
### PROMPT: 
 "Translate the following into Spanish "I have Class tomorrow"."
### OUTPUT: 
 "Tengo clase mañana."

### PROMPT: 
"Translate the following into German "It rains today"."
### OUTPUT: 
"Es regnet heute."
 
### 2. Story Generation:
### PROMPT: 
"write a short story on a scientist new discovery"
### OUTPUT:
"The Spark of Discovery":
 Dr. Maya Verma had always been fascinated by the invisible. While others saw the sky as endless blue, she saw hidden patterns—tiny movements of air, whispers of energy yet to be understood.
 One late night in her lab, surrounded by humming machines and the smell of burnt coffee, she noticed something unusual in her data. The particles she was studying weren’t behaving randomly. They were moving in a rhythm, almost like they were communicating.
 She repeated the experiment dozens of times, each test confirming her suspicion. These microscopic signals could carry information—faster and more efficiently than anything known before. It was as if nature had been hiding a secret network, waiting for someone curious enough to listen.
 After weeks of testing and sleepless nights, Maya realized she had discovered a new method of communication, one that could revolutionize how humans send data across the world. Her hands trembled as she wrote in her journal: “The invisible has spoken—and I finally heard it.” For the first time, she wasn’t just a scientist chasing answers. She was the scientist who had uncovered a new way for humanity to connect."

### PROMPT: 
"write a short story on a new element discovery"
### OUTPUT:
The Hidden Flame

Dr. Anaya Patel had spent years studying the tiniest fragments of matter, chasing mysteries most people never imagined. One night, in her quiet laboratory, she noticed something unusual in the spectrometer: a glow that didn’t match any known element. It shimmered like liquid fire, but cool to the touch.

Skeptical, she repeated the experiment. Each time, the same strange signal appeared. After weeks of careful testing, she realized she had uncovered a new element—one that emitted energy without burning, stable yet endlessly powerful. She named it Ignisium, the hidden flame.

News of her discovery spread across the world. Some dreamed of limitless clean energy; others feared its power. But for Anaya, it wasn’t about fame or fear. It was about proving that even in the smallest corners of nature, there were secrets waiting patiently to be found.

And that night, staring at the glow, she whispered to herself, “The universe still has stories left to tell.”

### 3. Fill-in-the-Blanks / Cloze Tasks:
### PROMPT: 
"The scientist conducted the experiment ______ and recorded the results meticulously"
### OUTPUT:
carefully → The scientist conducted the experiment carefully and recorded the results meticulously.
### PROMPT: 
Due to _______ rainfall this year, there will be a ______ cut in the water supply.
### OUTPUT:
Due to low rainfall this year, there will be a major cut in the water supply.

### 4. Counterfactual Reasoning:
### PROMPT: 
"if internet doesn't exist what would happen to the communication and information sharing."
### OUTPUT:
If the internet didn’t exist, communication and information sharing would be very different:

. Slower Communication

  People would rely heavily on letters, landline telephones, fax machines, and face-to-face meetings.
  Long-distance communication would take days or weeks instead of seconds.

. Limited Information Access

  Knowledge would mainly come from books, newspapers, magazines, radio, and television.
  Finding information would require visiting libraries or experts instead of searching online.

. Restricted Global Connectivity

  International collaboration in science, business, and education would be slower.
  People from different countries would connect far less often, making the world feel “bigger” and less connected.

. Dependence on Physical Media
  
  Information would be shared through printed reports, floppy disks, CDs, or USB drives rather than instant digital transfer.
  Music, movies, and news would spread much more slowly.

. Social Impact
  
  No social media, instant messaging, or video calls. Relationships would depend more on in-person interactions.
  Local communities might feel stronger, but global awareness would be weaker.

. Innovation and Economy
  
  Many modern industries (like e-commerce, online education, cloud computing, AI, remote work) would not exist.
  Business growth and global trade would be slower.

👉 In short, communication and information sharing would be much slower, more localized, and less accessible, and the world would feel less connected.

### PROMPT: 
“Imagine a world without music. What would be different about society, and how would it impact human emotion and connection?”
### OUTPUT: 
A world without music would feel quieter, emptier, and less expressive. Music is deeply tied to human emotion; it comforts, excites, and unites people. Without it, celebrations like weddings, festivals, and cultural ceremonies would lose an essential layer of joy and meaning. Emotional expression might become more limited, as music allows feelings to be communicated beyond words. Social bonding could also weaken, since shared musical experiences—concerts, dances, or even singing together—play a key role in forming communities. Art, entertainment, and even education would be less dynamic, as music often enhances learning and creativity. Overall, a world without music would still function, but it would lack a universal language that connects hearts, sparks imagination, and gives rhythm to life itself.

### 5. Code Generation:
### PROMPT: 
"Write a javascript program to find sum of two variable and return sum"
### OUTPUT: 
```js
function findSum(a, b) {
    return a + b;
}

// Example usage
let num1 = 10;
let num2 = 20;
let sum = findSum(num1, num2);

console.log("The sum is:", sum);
```
### PROMPT:
"Write a c program to find average of two numbers and return average"
### OUTPUT:
```c
#include <stdio.h>
float findAverage(int a, int b) {
    return (a + b) / 2.0;
}
int main() {
    int num1, num2;
    float avg;
    printf("Enter first number: ");
    scanf("%d", &num1);
    printf("Enter second number: ");
    scanf("%d", &num2);
    avg = findAverage(num1, num2);
    printf("The average is: %.2f\n", avg);
    return 0;
}
```

### 6. Trivia Questions:
### PROMPT: 
"who was the 3rd president of india"
### OUTPUT: 
The 3rd President of India was Dr. Zakir Husain.

He served from 13 May 1967 until his death on 3 May 1969.

He was the first Muslim President of India.

Before becoming President, he was the Vice President of India (1962–1967) and also a noted educationist.

### PROMPT: 
"who was the first engineer in india"
### OUTPUT: 
The title of the first engineer of India is often attributed to Mokshagundam Visvesvaraya (1861–1962).

He was a civil engineer, scholar, and statesman.

Famous for his work on the Krishna Raja Sagara Dam in Mysore and designing an innovative automatic water floodgate system.

Honored with the Bharat Ratna in 1955.

His birthday, 15 September, is celebrated as Engineers’ Day in India every year.

### 7. Cause and Effect:
### PROMPT: 
"what is likely to happen if it snows for several days."
### OUTPUT: 
If it snows for several days in a row, several things are likely to happen:

### Snow Accumulation

Roads, rooftops, and open areas will be covered with thick layers of snow.

Travel and transportation may become difficult or even impossible in some places.

### Transportation Disruptions

Flights, trains, and buses may be delayed or canceled.

Roads can become slippery and hazardous, leading to accidents.

### Daily Life Impact

Schools and offices may close.

Power outages can occur if heavy snow damages power lines.

People may be confined indoors for safety.

### Resource Shortage

Delivery of essential supplies like food, fuel, and medicine may be delayed.

Shops might run out of stock if snowfall continues.

### Environmental Effects

Snow insulates the ground, protecting plants from extreme cold.

Heavy snow can break tree branches or collapse weak structures.

### Health Concerns

People may suffer from cold-related illnesses (frostbite, hypothermia).

Risk of slipping and falling increases.

👉 In short, prolonged snowfall can cause major disruptions in transport, daily life, and resources, but it also creates a protective blanket for nature.

### PROMPT: 
"What is likely to happen if air completely disappeared for a minute?"
### OUTPUT: 
If air completely disappeared for just one minute, the effects would be catastrophic:

### Immediate Breathing Crisis

Humans and animals would be unable to breathe. Many would lose consciousness within 10–15 seconds due to lack of oxygen.

### Collapse of Pressure

Air provides atmospheric pressure. Without it, the pressure difference would cause fluids in the body to boil at normal body temperature, leading to swelling and severe damage.

### Structural Damage

Buildings, vehicles, and even the human body rely on air pressure. The sudden vacuum could cause windows to shatter, eardrums to burst, and weak structures to collapse.

### Fires Would Extinguish

Since fire needs oxygen, all flames would instantly go out, including stoves, power plants, and engines.

### Sky Turns Black

Air scatters sunlight to make the sky blue. Without it, the sky would turn pitch black, even in daytime, and the Sun would look like a sharp white disk.


### 8. Object Counting:
### PROMPT: 
"In the sentence ‘I saw five parrot, two dove, and four cats,’ how many birds are there?”
### OUTPUT: 
7 birds.

### PROMPT:
"In the sentence ‘I saw three monkey, two peacock, and four rats,’ how many animals are there?”
### OUTPUT:
9 animals.


### 9. Multi-lingual Tasks:
### PROMPT: 
Books bombarded his shoulder, his arms, his upturned face.  A book lit, almost obediently, like a white pigeon, in his hands, wings fluttering.  In the dim, wavering light, a page hung open and it was like a snowy feather, the words delicately painted thereon.  In all the rush and fervor, Montage had only an instant to read a line, but it blazed in his mind for the next minute as if stamped there with fiery steel.  “Time has fallen asleep in the afternoon sunshine.”  He dropped the book.  Immediately, another fell into his arms.”
Translate this paragraph into Spanish and then summarize it in English.”
### OUTPUT:
Spanish Translation:

Los libros bombardearon su hombro, sus brazos, su rostro vuelto hacia arriba. Un libro cayó, casi obedientemente, como una paloma blanca, en sus manos, con las alas revoloteando. En la tenue y vacilante luz, una página quedó abierta y era como una pluma nevada, las palabras delicadamente pintadas en ella. En todo el apuro y fervor, Montag solo tuvo un instante para leer una línea, pero esta ardió en su mente durante el siguiente minuto como si hubiera sido estampada allí con acero candente. “El tiempo se ha dormido en la luz de la tarde.” Dejó caer el libro. Inmediatamente, otro cayó en sus brazos.

English Summary:

Montag is overwhelmed by falling books. One lands gently in his hands, and in the brief moment he reads a line—“Time has fallen asleep in the afternoon sunshine”—which burns into his memory. He drops the book, and another quickly takes its place.

### PROMPT: 
What they do not comprehend is man’s helplessness. I am weak, small, and of no consequence to the universe. It does not notice me; I live on unseen. But why is that bad? Isn’t it better that way? Whom the gods notice they destroy. But small...and you will escape the jealousy of the great. Translate this paragraph into russian and summarize it in english
### Output:
Russian Translation:

Они не понимают бессилия человека. Я слаб, мал и не имею никакого значения для вселенной. Она не замечает меня; я живу незамеченным. Но разве это плохо? Разве так не лучше? Кого замечают боги, того они уничтожают. Но будь малым... и ты избежишь зависти великих.

English Summary:

The speaker reflects on human insignificance, suggesting that being unnoticed by the universe is not a curse but a protection. Those who draw the attention of powerful forces often suffer, while those who remain small and unseen escape destruction.

### 10. Task Prioritization:
### PROMPT: 
Given the tasks of 'planning a vacation,' 'deep cleaning the garage,' and 'organizing your digital photos,' which should you do first and why?
### Output:
Deep cleaning the garage → This is the most physically demanding and time-sensitive task. Once it’s done, it clears space, reduces stress, and gives a sense of accomplishment. It’s better to tackle heavy chores first when energy is high.

Organizing your digital photos → This is less urgent and can be done gradually, even during downtime. It’s important, but not physically exhausting.

Planning a vacation → This is the most enjoyable task, so saving it for last works as a reward after completing the harder jobs.

### Prompt:
"Imagine you have a big project due tomorrow, a friend's birthday party tonight, and a pile of laundry to do. How would you prioritize these tasks and what factors would you consider?"
### Output:
Big project due tomorrow → This has a hard deadline and serious consequences if not done. It should come first.

Friend’s birthday party → Important for maintaining relationships, but it depends on how much time the project needs. If possible, attend after making solid progress.

Laundry → Least urgent. It can wait until after the project or even the next day unless absolutely necessary (e.g., no clean clothes).

# RESULT:
Thus various prompts are experimented and improved the performance in complex reasoning and creative tasks.
