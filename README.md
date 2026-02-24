# Diagramme de classes :

![WhatsApp Image 2026-02-24 at 1 18 09 AM](https://github.com/user-attachments/assets/43d674d4-bf69-44b5-aab5-dd989c392b66)
<br></br>
# Analyse des Relations et des Annotations :
<br></br>
## Utilisateur – Reservation:
Il existe une relation OneToMany / ManyToOne entre ces deux entités.
Un utilisateur peut effectuer plusieurs réservations au fil du temps. En revanche, chaque réservation est associée à un seul utilisateur.
<br></br>
## Reservation – Salle:
La relation entre Reservation et Salle est de type ManyToOne / OneToMany.
Chaque réservation concerne une seule salle précise. Cependant, une même salle peut faire l’objet de plusieurs réservations à des dates différentes.
<br></br>
## Salle – Equipement:
Ces deux entités sont liées par une relation ManyToMany.
Une salle peut être équipée de plusieurs équipements . De  même, un même équipement peut être installé dans plusieurs salles.
<br></br>
# Exécution du projet:
<br></br>
<img width="1918" height="1007" alt="Capture d&#39;écran 2026-02-23 210955" src="https://github.com/user-attachments/assets/83850da9-cf3d-4683-9912-25388b054359" />
<br></br>

# Exécution la Classe App:
<br></br>
<img width="1919" height="1001" alt="Capture d&#39;écran 2026-02-23 115830" src="https://github.com/user-attachments/assets/e1a0edd4-7aae-4c89-ba84-11581b8d0602" />
<img width="1027" height="749" alt="Capture d&#39;écran 2026-02-23 120005" src="https://github.com/user-attachments/assets/f8777fef-cae8-4f4a-8453-f6d40f8d7431" />
<img width="957" height="902" alt="Capture d&#39;écran 2026-02-23 120121" src="https://github.com/user-attachments/assets/6dac2266-7b9b-4fad-a1f6-852d09426aa0" />
<img width="1037" height="903" alt="Capture d&#39;écran 2026-02-23 120156" src="https://github.com/user-attachments/assets/9daf4c61-8a51-4f52-a7f8-540c14b706ca" />
<img width="1101" height="898" alt="Capture d&#39;écran 2026-02-23 120256" src="https://github.com/user-attachments/assets/c398e1b4-66fd-44aa-bae4-635c46e764d9" />
<img width="1236" height="895" alt="Capture d&#39;écran 2026-02-23 120333" src="https://github.com/user-attachments/assets/a442d665-69f7-4c8f-9105-a2d886c225ca" />
<img width="973" height="893" alt="Capture d&#39;écran 2026-02-23 120405" src="https://github.com/user-attachments/assets/96d82b93-80aa-43f1-9b3a-6b7267faff79" />
<img width="1047" height="896" alt="Capture d&#39;écran 2026-02-23 120444" src="https://github.com/user-attachments/assets/36db069e-03a4-4a5a-abb0-c32e2b9b1eac" />
<img width="801" height="891" alt="Capture d&#39;écran 2026-02-23 120501" src="https://github.com/user-attachments/assets/e8ac72d7-16fc-4628-b25a-60693264682d" />
<img width="1018" height="901" alt="Capture d&#39;écran 2026-02-23 120518" src="https://github.com/user-attachments/assets/d2043a90-a620-4ad5-891f-c3951185bd17" />
<img width="828" height="897" alt="Capture d&#39;écran 2026-02-23 120536" src="https://github.com/user-attachments/assets/0e1457dc-e556-4503-82b5-dd64aa62ee98" />
<img width="687" height="897" alt="Capture d&#39;écran 2026-02-23 120555" src="https://github.com/user-attachments/assets/da9305f7-4f0f-4ec2-ac06-b6ba8b4b3199" />
<img width="713" height="899" alt="Capture d&#39;écran 2026-02-23 120608" src="https://github.com/user-attachments/assets/2eea6403-3958-41fa-81d3-5ce98cdf8b89" />
<img width="829" height="893" alt="Capture d&#39;écran 2026-02-23 120627" src="https://github.com/user-attachments/assets/21ca7bcf-aaae-4c36-9978-0061e12ceaa1" />
<img width="992" height="893" alt="Capture d&#39;écran 2026-02-23 120647" src="https://github.com/user-attachments/assets/8a902d16-6521-4801-94cd-437a2afa1eab" />
<img width="893" height="902" alt="Capture d&#39;écran 2026-02-23 120745" src="https://github.com/user-attachments/assets/e12d566b-5f9e-4b21-868c-261c2017a14b" />
<img width="890" height="904" alt="Capture d&#39;écran 2026-02-23 120807" src="https://github.com/user-attachments/assets/8a04a9db-fa60-4f09-b58f-af0a57322570" />
<img width="746" height="894" alt="Capture d&#39;écran 2026-02-23 120819" src="https://github.com/user-attachments/assets/4bfa324d-4d61-4d5c-ad27-3e4ff0ab9cb0" />
<img width="790" height="892" alt="Capture d&#39;écran 2026-02-23 120835" src="https://github.com/user-attachments/assets/6bcfb7cc-9da0-40e6-9932-f5e7f4aea153" />
<img width="966" height="902" alt="Capture d&#39;écran 2026-02-23 120850" src="https://github.com/user-attachments/assets/9f9ee47f-7ab2-4c57-b376-8f90aaade7f4" />
<img width="958" height="901" alt="Capture d&#39;écran 2026-02-23 121000" src="https://github.com/user-attachments/assets/e0be558e-c9f9-45e7-aec7-e9e5433391c8" />
<img width="849" height="899" alt="Capture d&#39;écran 2026-02-23 121014" src="https://github.com/user-attachments/assets/14b20d52-9030-4baa-bb3a-265eb047711a" />
<img width="1843" height="895" alt="Capture d&#39;écran 2026-02-23 121042" src="https://github.com/user-attachments/assets/978043a6-7e17-4269-ba95-2c4ebb7f5101" />
