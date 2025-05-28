Playbook który pobiera aplikacje z danego repozytorium na nexusie i wrzuca na odpowiednie tomcaty. 
Użycie= odpalasz na serverze gdzie jest ruch do hosta. ansible-playbook -i hosts deploy.yaml
Zmiany wykonujesz w pliku versions.yaml - tylko te aplikacje które są tam wymienione wraz z wersjami zostaną zdeployowane. 
