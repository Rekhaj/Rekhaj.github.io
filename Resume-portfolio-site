export default function Portfolio() {
  return (
    <main className="max-w-5xl mx-auto p-6 text-gray-800 space-y-10">
      <section className="text-center">
        <h1 className="text-4xl font-bold">AI & Computer Vision Specialist</h1>
        <p className="mt-2 text-lg">Experienced in 3D Imaging, Deep Learning & Medical Tech Solutions</p>
      </section>

      <section>
        <h2 className="text-2xl font-semibold border-b pb-2">Professional Summary</h2>
        <p className="mt-2">
          Experienced AI and Computer Vision specialist with a strong background in 3D imaging, deep learning, and medical technology solutions. Passionate about leveraging state-of-the-art machine learning techniques to drive impactful innovations. Seeking opportunities to contribute expertise in AI-driven healthcare and digital medical solutions.
        </p>
      </section>

      <section>
        <h2 className="text-2xl font-semibold border-b pb-2">Professional Experience</h2>
        <div className="space-y-4 mt-4">
          <Job 
            title="Computer Vision Engineer" 
            company="Ottobock SE & Co. KGaA, Berlin" 
            period="Sep 2021 – Sep 2023" 
            details={[
              "Led development of deep learning models for gait analytics, estimating biomechanical parameters for prosthetic patients.",
              "Conducted research in human activity recognition to enhance rehabilitation processes.",
              "Benchmarked biomechanical parameters using multi-camera gait analysis on diverse walking surfaces.",
              "Managed and coordinated an analytics team for successful project execution."
            ]} 
          />

          <Job 
            title="Scientific R&D Engineer" 
            company="Fraunhofer HHI, Berlin" 
            period="Sep 2018 – Sep 2020"
            details={[
              "Developed AI-driven gesture recognition and 3D face-hand tracking systems.",
              "Designed 3D reconstruction models for robotic manipulation.",
              "Implemented 2D/3D pose estimation techniques for human movement analysis.",
              "Researched multimodal human-computer interaction and sensor data fusion."
            ]}
          />

          <Job 
            title="Scientific R&D Engineer" 
            company="Fraunhofer IAPT, Hamburg" 
            period="Jan 2018 – Aug 2018"
            details={[
              "Developed quality assurance systems for additive manufacturing.",
              "Applied computer vision techniques for in-process monitoring in 3D metal printing.",
              "Integrated and analysed sensor data for real-time process optimization."
            ]}
          />

          <Job 
            title="Research Associate & Staff" 
            company="LZN Nord GmbH, Hamburg" 
            period="May 2016 – Dec 2017"
            details={[
              "Designed and developed 3D vision systems for laser welding automation.",
              "Calibrated cameras and processed 3D data for robotic welding applications."
            ]}
          />

          <Job 
            title="Research Associate & Staff" 
            company="University of Hamburg" 
            period="Apr 2012 – Apr 2016"
            details={[
              "Led projects on motion tracking, gesture recognition, and stereo vision analysis.",
              "Integrated 3D sensors for facial expression and body movement tracking.",
              "Supervised Bachelor’s and Master’s theses in computer vision applications."
            ]}
          />

          <Job 
            title="Scientist - C" 
            company="CMERI-CSIR, India" 
            period="Nov 2011 – Mar 2012"
            details={[
              "Developed obstacle avoidance systems for surface robotics.",
              "Designed AI-based Indian Sign Language interpretation prototype."
            ]}
          />

          <Job 
            title="Software Engineer Trainee" 
            company="AU-KBC Research Centre-MIT, Chennai, India" 
            period="Jun 2009 – Sep 2009"
            details={[
              "Developed web applications using open-source frameworks.",
              "Managed software development lifecycle processes."
            ]}
          />

          <Job 
            title="Full-Time Caregiver" 
            company="Personal" 
            period="Jan 2024 – Jan 2025"
            details={[
              "Managed medical schedules, financial planning, and coordinated healthcare logistics for a terminally ill parent until their passing."
            ]}
          />
        </div>
      </section>

      <section>
        <h2 className="text-2xl font-semibold border-b pb-2">Technical Skills</h2>
        <ul className="list-disc list-inside mt-2 columns-2">
          <li>Generative AI, Prompt Engineering</li>
          <li>C/C++, Python</li>
          <li>OpenCV, scikit-learn, Dlib, Mediapipe, OpenPose</li>
          <li>PyTorch, TensorFlow, Keras (CNNs), YOLO, OpenMMLab</li>
          <li>Azure Kinect, RealSense, Stereo Vision, Hyperspectral Imaging</li>
          <li>GitHub, GitLab, Azure DevOps, CMake</li>
          <li>Microsoft Azure</li>
          <li>PCL, Open3D, KUKA Robotics</li>
        </ul>
      </section>

      <section>
        <h2 className="text-2xl font-semibold border-b pb-2">Education</h2>
        <ul className="mt-2">
          <li><strong>Master’s in Mechatronic Engineering</strong> — AcSIR University, Delhi, India (2009 – 2011)</li>
          <li><strong>Bachelor’s in Computer Science Engineering</strong> — Anna University, Chennai, India (2005 – 2009)</li>
        </ul>
      </section>

      <section className="text-center">
        <p className="mt-6 text-sm text-gray-500">Interested in collaborating or hiring? Let’s connect!</p>
        <p className="font-medium">Email: your.email@example.com</p>
      </section>
    </main>
  );
}

function Job({ title, company, period, details }) {
  return (
    <div className="border-l-4 border-blue-500 pl-4">
      <h3 className="text-xl font-semibold">{title}</h3>
      <p className="italic text-sm">{company} | {period}</p>
      <ul className="list-disc list-inside mt-1">
        {details.map((d, i) => <li key={i}>{d}</li>)}
      </ul>
    </div>
  );
}
