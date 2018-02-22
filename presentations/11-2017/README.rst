.. code-block:: yaml

    - name: Ansible Meetup
      hosts: Red Hat Montreal Office
      vars:
        date: 11-22-2018
        link: https://www.meetup.com/Ansible-Montreal/events/244352092/
        sponsors:
          - CloudOps for Pizza
          - Red Hat for beverages
      tasks:
        - name: Nouvelles Ansible
          presentation:
            by: Michael Lessard, Red Hat
            document: 01-nouvelles.pdf
            abstract: |
              Ansible 2.4, Ansible Engine + Networking, Ansible Tower 3.2 et
              courte démonstration d'Ansible AWX.

        - name: Ansible au LanETS
          presentation:
            by: Laurent Dumont, LanETS
            document: 02-lanets.pdf
            abstract: |
              Lan ETS / Dreamhack - Exploiter Ansible et l'automatisation
              pour traiter la programmation de l'infrastructure
              (infrastructure as code) - de zéro à 100%

        - name: Mise à jour sur ARA 1.0
          presentation:
            by: David Moreau Simard, Red Hat
            document: 03-ara.pdf
            abstract: |
              Un bref aperçu des nouvelles fonctionnalités et du progrès pour
              la nouvelle version majeure d'ARA

        - name: Molecule, isoler le dévelopement des rôles
          presentation:
            by: Alain Chiasson
            document: 04-molecule.pdf
            abstract: |
              Avec L’aide des outils Molécule et TestInfra, et l’application
              de la méthodologie de développement par Test
              (TDD - Test Driven Development), nous allons démontrer le pouvoir
              de la programmation de l'infrastructure (infrastructure as code)
              vérifiable dans le développement de rôles Ansible.

        - name: Software Factory, Développer, Tester et Valider vos rôles et playbooks Ansible
          presentation:
            by: Nicolas Hicher
            document: 05-software-factory.pdf
            abstract: |
              Dans cette présentation, nous verrons comment utiliser une
              plateforme d'intégration et de déploiement continu pour
              développer, tester et déployer vos playbooks et rôles Ansible.
              Nous utiliserons Software-Factory, une forge logicielle qui
              permet de centraliser et d'automatiser votre validation.
