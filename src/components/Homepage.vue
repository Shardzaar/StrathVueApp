<template>
    <div id = 'homepage'>
        <v-container>
                <v-layout column>
                    <v-carousel>
                        <v-carousel-item
                            src="./../../public/wonderlane-6zlgM-GUd6I-unsplash.jpg"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="./../../public/wan-san-yip-ID1yWa1Wpx0-unsplash.jpg"
                            cover
                        ></v-carousel-item>

                        <v-carousel-item
                            src="./../../public/pexels-pixabay-159740.jpg"
                            cover
                        ></v-carousel-item>
                    </v-carousel>
                    </v-layout>
                    <v-layout>
                    <v-container>
                        <v-row align="center" justify="center">
                            <div class="d-flex align-center flex-column">
                                <div class="text-subtitle-2">With props</div>

                                <v-card
                                width="400"
                                title="Student Life"
                                subtitle="From the Student President"
                                text="
Student life is a vibrant tapestry woven with a myriad of experiences, challenges, and opportunities. It's a time of exploration, growth, and self-discovery, marked by a delicate balance between academics, extracurricular activities, and social interactions.

At the heart of student life lies the pursuit of knowledge. Whether delving into the depths of calculus or dissecting the nuances of Shakespearean literature, students are constantly engaged in the quest for intellectual enlightenment. From early morning lectures to late-night study sessions, the academic journey is both demanding and rewarding, pushing students to expand their horizons and challenge their intellects.

Yet, student life is not solely confined to the confines of the classroom. It's also a bustling ecosystem of clubs, organizations, and extracurricular pursuits. From joining a debate team to volunteering for a local charity, students have countless opportunities to explore their passions, develop new skills, and forge lifelong friendships. These extracurricular activities not only enrich the college experience but also foster personal growth and character development.

Amidst the academic rigor and extracurricular engagements, students also navigate the intricacies of social life. From dormitory hangouts to campus parties, from deep conversations in coffee shops to spontaneous adventures, student life is a vibrant social tapestry where connections are forged and memories are made. It's a time of camaraderie, laughter, and shared experiences, as students bond over common interests and navigate the complexities of relationships.

In essence, student life is a multifaceted journey filled with excitement, challenges, and endless possibilities. It's a time of academic pursuits, extracurricular adventures, and social connections, all woven together to create a rich tapestry of experiences that shape the trajectory of one's life. And as students navigate the highs and lows of this transformative journey, they emerge not only with a degree in hand but also with a wealth of memories, lessons, and friendships that will last a lifetime."
                                ></v-card>

                                <div class="mt-4 text-subtitle-2">With slots</div>

                                <v-card width="400">
                                <template v-slot:title>
                                    Accomodation
                                </template>

                                <template v-slot:subtitle>
                                    From the Hospitality department
                                </template>

                                <template v-slot:text>
                                    
Accommodation in universities is a vital aspect of student life, providing a home away from home for students embarking on their academic journey. From cozy dormitories to modern apartment complexes, universities strive to offer a range of housing options to suit the diverse needs and preferences of their student population. These accommodations serve as more than just living spaces; they are vibrant communities where students forge lifelong friendships, engage in academic collaborations, and partake in a myriad of social and cultural activities. With amenities such as study lounges, fitness centers, and communal kitchens, university accommodations are designed to foster a supportive and enriching environment conducive to both academic success and personal growth. Additionally, living on campus often facilitates easy access to campus resources, such as libraries, dining halls, and recreational facilities, further enhancing the overall student experience. In essence, university accommodation plays a pivotal role in shaping the college experience, providing students with not just a place to live, but a vibrant community to thrive in as they navigate the exciting journey of higher education.
                                </template>
                                </v-card>

                                <div class="mt-4 text-subtitle-2">With markup</div>

                                <v-card width="400">
                                <v-card-item>
                                    <v-card-title>Clubs</v-card-title>

                                    <v-card-subtitle>From the Clubs Department</v-card-subtitle>
                                </v-card-item>

                                <v-card-text>
                                    
Club life on college campuses is a vibrant and dynamic aspect of student culture, offering a diverse array of opportunities for involvement and personal growth. From academic and professional organizations to special interest and hobby-based clubs, there is something for everyone to explore and engage with. These clubs serve as invaluable platforms for students to pursue their passions, develop leadership skills, and build lasting friendships with like-minded individuals. Whether it's participating in a debate club, joining a sports team, or immersing oneself in cultural or artistic pursuits, club involvement fosters a sense of belonging and community within the campus ecosystem. Moreover, club activities often extend beyond the confines of the university, providing students with opportunities for networking, community service, and even career advancement. Club life enriches the college experience by offering a space for creativity, collaboration, and personal development, ultimately contributing to the holistic growth and well-being of students during their academic journey.
                                </v-card-text>
                                </v-card>
                            </div>
                        </v-row>
                    </v-container>
                </v-layout>
            </v-container>
    </div>
</template>
<script setup>
  const variants = ['elevated', 'flat', 'tonal', 'outlined']
</script>