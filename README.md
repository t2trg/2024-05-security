# T2TRG 2024-05 Interim Meeting on IoT Security
T2TRG Interim Meeting on IoT security implementation, operation, and systems aspects.

Co-located with the ["Hackathon on Lightweight IoT Security"](https://parishackathon.lakewg.org/program/) in Paris on May 21/22 2024.

This interim will start with a hybrid (online/on-site) meeting from 17:00 to 18:45 (CEST, i.e. 1500Z to 1645Z) on May 21st.
We also will have an opportunity to run some ad-hoc breakout meetings (also hybrid) on May 22nd in the morning.

Local time in various locations:<br>
https://www.timeanddate.com/worldclock/fixedtime.html?msg=T2TRG+interim+on+security&iso=20240521T15&ah=1<br>

## Topic

IoT is moving away from closely coupling devices to a vendor cloud, towards enabling their integration into an infrastructure run by the device's operator or third parties of the device operator's choice.  This is especially true in traditional OT environments such as factories and commercial buildings.  The focus is shifting away from the connections that move data, towards the data themselves, including data about devices and their relationships.  Security is the crucial enabler, but can only work if it is well-informed about the structure of the data and the processes.

The usual areas of work continue to apply:

- Secure communication in structured groups and distributed environments
- Communication of security-relevant properties (provenance, posture, ...)
- Resilience against system security lapses (IoT device, distributed application components -- having enough information to be able to detect and react to unexpected situations)

However, these now need to be seen in the context of the emerging **device/infrastructure continuum**.  We plan to explore how devices and infrastructure can be melded more closely together so the device can rely on the infrastructure for some of its tasks and the infrastructure knows what to expect from the device. This includes looking at what the points of interaction are between components, both inside and between domains of authority.
Moving from a connection-oriented infrastructure to a data-oriented infrastructure enables rapid and sustainable application development, as well as more efficient transfer of information by the infrastructure that can leverage the knowledge of the purpose and expectations of the data and devices.
Elements enabling this continuum include distributed applications, distributed AI, efficient protocols that make use of the friends in the network, device management capabilities, etc. Open research issues include scalable and efficient modeling of data, naming data, proving provenance for processed and aggregated data, discovery and distribution of data, secure distributed processing of data.

We invite academics, engineers, and practitioners working on related topics to join the T2TRG interim to present and discuss the state of the art and future direction of secure and scalable IoT.


## Registration

Please indicate your interest by registering at: https://forms.gle/BQdpTshct1s7zRGj8

If you plan to be present physically, please register for the hackathon
as well: https://parishackathon.lakewg.org/register-here/

## Logistics

The interim meeting will take place at the premises of Inria Paris. See the [hackathon venue](https://parishackathon.lakewg.org/venue/) page for more details.

There is no attendance fee and the meeting is open for everyone to register and join.

Webex for remote participants: https://ietf.webex.com/ietf/j.php?MTID=ma80d5cdef59bfe4ea73960d78b18d6f0

This will start with a hybrid (online/on-site) meeting from 17:00 to 18:45 (CEST, i.e. 1500Z to 1645Z) on May 21st.  We also will have an opportunity to run some ad-hoc breakout meetings (also hybrid) on May 22nd in the morning.

## Materials

See the IETF Data Tracker page for the meeting: https://datatracker.ietf.org/meeting/interim-2024-t2trg-01/session/t2trg

## Draft Agenda

Please contact the [chairs][] for topic proposals or any other requests.

| Time (UTC) | Who            | Subject                                                                                       | Remarks   |
|------------|----------------|-----------------------------------------------------------------------------------------------|-----------|
| 2024-05-21 |                |                                                                                               |           |
|      15:00 | Chairs         | Intro                                                                                         |           |
|      15:10 | Rajat Kandoi / Ari Keränen    | Secure In-network Data Fabric for IoT applications                                            |           |
|      15:27 | Abhishek Kumar | How can AI be distributed in the computing continuum? Introducing the neural pub/sub paradigm | [paper][] |
|      15:44 | Renzo Navas    | Post-Quantum Cryptography: Overview and IoT Standardisation Perspectives                      |           |
|      16:01 | Marco Tiloca   | Distribution of Software Updates with End-to-End Secure Group Communication for CoAP          |           |
|      16:18 | Rikard Höglund | Using onion routing with CoAP                                                                 | [draft][] |
|      16:35 | Chairs         | Wrapup                                                                                        |           |
|      16:50 | Chairs         | End of day #1                                                                                 |           |
| 2024-05-22 |                |                                                                                               |           |
|    morning | ad-hoc         | Room for breakout discussions                                                                 |           |

[chairs]: mailto:t2trg-chairs@irtf.org
[paper]: https://arxiv.org/abs/2309.02058
[draft-dt]: https://datatracker.ietf.org/doc/draft-amsuess-t2trg-onion-coap/
[draft]: https://www.ietf.org/archive/id/draft-amsuess-t2trg-onion-coap-01.html
