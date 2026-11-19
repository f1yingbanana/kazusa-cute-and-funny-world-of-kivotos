# Kivotos: World Wiki

The World Wiki for the Blue Archive world: what is true in Kivotos, the academy
city, as the main story stands after Volume 6. The Arius Squad is on parole, FOX
Squad works under SCHALE, and Mika is on probation. The player is Sensei
(`user:sensei`), SCHALE's adult advisor. ARONA (`arona`) is the system agent,
living in the Shittim Chest.

This page is for people and for ARONA, to find their way around. Characters
never read it, and the memory index skips it. Keep it high level: the folders
are the full listing.

## What's here

- `characters/`: 146 pages: 144 simulated students, ARONA, and Sensei (the
  player).
- `concepts/`: 857 pages. 720 are places (`place_id`), in 13 districts plus 14
  stations; 76 are groups (`group: true`): schools, clubs, councils, squads,
  gangs and companies. The rest is lore: story events and world rules. A school
  and its campus are one page, both a group and a place.

## Start with

- `concepts/kivotos_overview.md`: the root page. Halos, firearms, the General
  Student Council and SCHALE.
- `concepts/kivotos_geography.md`: where the districts lie relative to each
  other.
- `concepts/kivotos_transit.md`: Highlander's railways, the D.U. Metro, buses,
  and how long trips take.
- `concepts/student_housing.md`: dorms, curfews, and who lives elsewhere.
- `concepts/schale.md` and `concepts/schale_student_duty.md`: the SCHALE
  building and the weekly duty roster.
- One page per academy (`trinity_school.md`, `gehenna_school.md` and so on):
  the school, its campus, and the group its students are in. Its clubs link to
  it.

## The map

Districts are top-level areas, and each one is a town: a campus, dorms, a
shopping street, cafés and workplaces.

- **D.U. City** (`du_downtown`): the capital, with Sanctum Tower and D.U.
  Central Station. Inside it are Shiratori Ward (Tri-Square, Ramini Town,
  Kanesaki Port with Odyssey's berth, Valkyrie's campus) and Kousagi Ward
  (Kousagi Station Street, Kousagi Park with RABBIT's camp, and the SCHALE
  building).
- **Trinity**, **Gehenna**, **Millennium**, **Abydos**, **Hyakkiyako** and its
  **North District** (Ebisu), **Shanhaijing**, **Red Winter**, **Wild Hunt**:
  one district each.
- **Haruhabara Electric Town**, between D.U. and Millennium.
- **Black Market District**, south of Gehenna, toward Abydos.
- **Arius District**, below Trinity. It is reached only through the catacombs
  under the Old Cathedral of Communion.

Stations are top-level places too, joined by rail and Metro connections whose
times include the average wait. Typical trips to SCHALE: Trinity about 35
minutes, Gehenna and Millennium about 50, Abydos and Hyakkiyako about an hour,
Red Winter nearly two hours.

## The cast

- **Schools:**
  - Trinity 25, Gehenna 24, Millennium 25, Hyakkiyako 17, Red Winter 12
  - Shanhaijing 7, SRT 7, Wild Hunt 7, Abydos 5, Arius 5, Valkyrie 4, Highlander
    3, Odyssey 2
  - Rabu, a Trinity dropout
- **Homes:** every student has a private home, usually `room_<given name>` under
  her dorm. Canon exceptions: shared rooms at Wild Hunt, RABBIT's tents, Aris
  and Yuzu in the Game Development club room, Koyuki in the Self-Reflection
  Room, and hideouts for Rio, Kasumi and Wakamo.
- **Groups:** each student's page lists the groups she is in (`in`), with how
  involved she is: her school, her club or committee, her squad.
- **Workspaces:** each student's knowledge of places is her cards in
  `workspaces/<id>/wiki/concepts/`. Her weekly routine is the `## My usual week`
  section of her `MEMORY.md`.

## Conventions to keep

- Place names and aliases are unique across the world, and never equal a
  concept's title. Use "Gehenna Dining Hall", never "Dining Hall".
- Homes and hideouts have no `known`, and are never on a route between two other
  places.
- Who knows a page is said by groups (`known`); pages relate by `[[links]]` in
  their text, never by a `parent` outside the map.
- Summaries carry hours, locks and curfews, and never name a simulated student:
  the model would think she is there.
- A routine names at most five places by their exact world names. Places named
  in `MEMORY.md` take a character's "Places you know" slots first.
- Canon wherever the game says something. Most dorm names, the rail line names,
  the D.U. Metro's operator and the overall layout of the map are invented to
  fill gaps. In-world pages state them plainly, without flags.
