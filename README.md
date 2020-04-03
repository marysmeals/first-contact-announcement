# First Contact - COVID19 Tracking App

## MISSION
We're working on a truly functional Contact Tracing App to contain COVID19 spreading. It will keep a local log of all your close encounters with other individuals, detected via measuring Bluetooth signal strength, while you're outside of your defined safe zone (usually your home). If later on, one of those individuals will become a Covid19 confirmed case or will experience some Covid19 symptoms, you will be alerted through the app. You might then decide to self-isolate better, avoid contact with vulnerable persons and monitor your own health. If some symptoms do appear, you will be able to report them through the app, get localized guidelines on what to do next or even request an at-home Covid19 Test, if such a service will become available in your area, via Government Agencies or NGOs. The app will respect your privacy by anonymizing all contacts and will protect all your data by using encryption. While you're healthy, all your contact tracing data will NOT leave your phone. When you report an infection or symptoms, with your approval, the data will be sent to a server where it will be decrypted and analyzed in order to alert your contacts in an anonymized way. You might fill in a questionnaire about the kind of interactions you had at various times and locations.

## WHY WE'RE DOING IT
WHO recommends social distancing and extensive COVID19 testing as the 2 main methods for containing or slowing down the spread of the pandemic. The main issue is that this disease is constantly one step ahead of the authorities because of the initially asymptomatic carriers that manage to spread it further, before realizing they have been infected. Theoretically, if we could perfectly identify and isolate all the current Covid19 cases and their contacts, we could eradicate the disease in a couple of weeks and save innumerable lives. We need a smart solution to this problem based on the technologies readily available to the general public. Tracing proximity contacts is the most important gain we could get in the fight against COVID19. This has already been attempted with significant success in China, Singapore (TraceTogerer), Israel and other places. There are technically viable ways of doing this while still preserving the privacy of individuals. The solution would only work if it would gain massive adoption, at least in selected countries or regions. Alternatively, the app should be made interoperable with other similar apps, such that the tracing would work across apps and country borders. Ideally, the governments should get behind these efforts and push for faster adoption, while guaranteeing better data safety & privacy. The app would also inform authorities on the real field situation, allowing them to better concentrate their testing capabilities to those who really need it.

## WHO WE ARE
We're an NGO based in Romania and want to offer the Romanian public a possible solution for COVID19 contact tracing. Until now, there are no such apps in the Romanian language, aimed at the Romanian public and we are not aware of any government initiative in this area. The testing capabilities of the authorities are still limited and there is no way to know where to focus that testing. Romania has adopted early a lockdown strategy, but that alone is not working well enough and the numbers keep rising on a curve similar to Italy at the equivalent stage. We hope to be able to assist authorities and protect the public with this app.

However, if our solution will prove to be efficient and safe, we hope that it will be applied elsewhere as well, adapted or modified in any way. We plan to keep the full source-code entirely open from day 1 here on GitHub, under a permissive MIT License and give it to anyone for scrutiny, modifications, inspiration, etc.

## WE NEED HELP
We need to assemble a small team of volunteers that are willing and able to work intensively on this, so we get a Minimum Viable Product launched as soon as possible, with just the core features and minimal UI, so we can start testing this in the real world and continue to gather support for it.
We need at least one person for each of the following roles:
- Android native developer (Java/Kotlin, ideally with experience on Bluetooth and Location APIs)
- iOS native developer (Swift/iOS, ideally with experience on Bluetooth and Location APIs)
- Backend developer (NodeJS, Python or something else)
- Medic / Epidemiologist to help us with the in-app symptoms questionnaire and guidelines
- UI/Graphical Designer (logo, app GUI, simple presentation website)
- Tester

If you think you might be able to help with any of the above, or just want to talk to us about the project, you can reach us at valentin.radoi@gmail.com or over Skype at https://join.skype.com/invite/kvFCKSZVFbmR

## GOALS
- Have a Minimum Viable Product launched as soon as possible, ideally in a matter of days. We can improve and extend it through future updates, but it's critical to get it going right away before COVID19 becomes too wide-spread.
- Be fully transparent about the workflow of the app and data collection process, anonymizing procedures, data handling and storage, and privacy concerns. The app must fully comply with the GDPR requirements and all the applicable laws in EU countries.
- Align with other initiatives and integrate with any standards that can make our app interoperable with other similar efforts (more on this below)
- Use Bluetooth technology to detect when two phones with the app installed come close to each other, withing a few meters and try to approximate the distance based on radio signal strength, using an algorithm that takes the phone model into account. Also, measure the amount of time the two phones stay within close range. This, coupled later on with a user questionnaire will help us to determine a risk factor for a possible COVID19 transmission event, in case one of the two phones will belong to an infected person.
- Use GPS location optionally, only to pin-point the approximative close contact encountering on a map. No GPS location data should ever leave the phone of the user. This feature is still under debate!
- Provide users with a way to report if they got ill, either being a confirmed COVID19 case or just having some symptoms. The app would also provide advice on what do to next, based on the symptoms described in a questionnaire. We could use AI to assign a probability of COVID19 infection based on symptoms, contact tracing, and user's movements over the past 2 weeks.
- Have the ability to define safe-zones, usually at home, based on location or Wifi coverage. The app could disable the tracing while you're in our safe zone, where you would normally spend the vast majority of your time. When you exit the safe-zone, the app will activate contact tracing and notify you. When you return back to the safe zone, a summary of the encounters will be presented, and you'll have the ability to annotate some extra data on them (like where exactly you've been, if you interacted closely with someone there or not, if some of those contacts where persons you know already etc.). This will help later in assessing if any of those contacts could have been a COVID19 transmission event.

## OTHER SIMILAR INITIATIVES
* [Trace Together](https://www.tracetogether.gov.sg/) / [Blue Trace](https://bluetrace.io/)
* [Hamagen](https://medium.com/proferosec-osm/hamagen-application-fighiting-the-corona-virus-4ecf55eb4f7c)
* [Pan-European Privacy-Preserving Proximity Tracing (PEPP-PT)](https://www.pepp-pt.org/)
* [NextTrace](https://nexttrace.org/)
* [Community Epidemiology In Action (CoEpi)](https://www.coepi.org/)
* [LetsTrace.org](https://letstrace.org/)
* [COVID Safe Paths](https://covidsafepaths.org/)
* [COVID Watch](https://www.covid-watch.org/)
* [COVID19 Tracing](https://covid19tracing.org/)
* [CoronaTrace](https://corona-trace.github.io/)
* [ContactTracing](https://contacttracing.app/en/)
* [covid-app.io](https://www.covid-app.io/)
* [pandoa.org](https://pandoa.org/)
* [bandemic.app](https://bandemic.app/)
* https://github.com/enigmampc/SafeTrace
* https://github.com/ehidra/contact-tracer
* https://github.com/alexandrumeterez/covidtracer
* https://github.com/BDI-pathogens/covid-19_instant_tracing

## FINAL THOUGHTS
We are living through the biggest crisis of our generation (at least so far), and we don't know when and how it will end, but we know that we must act to make it better. The immediate action is to stay at home, but we need to do more than that. And, in this day and age, there are innovative solutions that can make a difference. Authorities are doing the best they can, but they seem to be overwhelmed by the situation and always one step behind the virus. We need to be proactive and use crowdsourcing and private initiatives to make an impact. All of us are still busy, even from home, and especially in the IT sector. There are always deadlines and ongoing commitments, but we must stop for a second and think that if we could do an app that would save even a couple of lives, that would be incommensurable. It will likely be the most important thing that we'll ever do in our lives.


