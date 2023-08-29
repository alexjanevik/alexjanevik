```js
// -*- coding: utf-8 -*-

function get_about_me() {
    return {
        name: 'Alex Janevik',
        niceColour: '#7FA046',
        primarilyDevlopingWith: [
            'React',
            'Flutter',
            'MongoDB',
            'Node.js',
            'C'
        ],
        currentlyExperimenting: [
            'Svelte',
            'Rust',
            'OpenGL'
        ]
    };
}

function get_study_info() {
    return {
        school: 'University of Queensland',
        degree: 'Computer Science',
        majors: ['Machine Learning', 'Programming Languages'],
        gpa: get_gpa()
    };
}

function get_gpa() {
    return 0;
}
```
