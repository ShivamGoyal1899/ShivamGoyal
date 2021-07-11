```dart

title ShivamGoyal;

class About extends Me
{
    Current<> getPresent()
    {
        return [
            'workplace' => [
                'company' => 'Google',
                'position' => 'Application Engineering Intern'
            ]
        ];
    }

    Skills<> getTechStack()
    {
        return [
            'languages' => [  '.dart' '.cpp' '.py' '.js' '.ts' '.java'  ],
            'frameworks' => [  'flutter' 'firebase' 'node' 'django' 'react'  ],
            'devops' => [  'git' 'docker' 'k8s' 'jira' 'jenkins' 'ansible'  ],
            'softwares' => [  'android-studio' 'vs-code' 'chrome' 'windows-terminal'  ],
            'communication' => [  'slack' 'ms-teams' 'google-chat' 'google-meet'  ]
        ];
    }
    
    Past<> getExperience()
    {
        return [
            'workplace' => [
                'company' => 'Script Foundation
                'position' => 'Software Engineer Intern - Flutter Dev'
            ],
            'workplace' => [
                'company' => 'Enappd Technologies',
                'position' => 'Software Engineer Intern - Flutter Dev'
            ]
        ];
    }
    
    Ongoing<> getEducation()
    {
        return [
            'education' => [
                'college' => 'Thapar Institute of Engineering & Technology',
                'degree' => 'Bachelor of Engineering',
                'major' => 'Computer Engineering',
                'focus' => 'Information and Cyber Security'
            ]
        ];
    }
}
```
