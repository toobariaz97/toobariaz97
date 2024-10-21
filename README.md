 <section id="home" className="mx-auto py-16  relative">
      <div className="">
        {/* Container for the gradient and avatar */}
        <div className="relative">
          {/* Responsive Gradient Background */}
          <div className="absolute left-5 top-10 inset-0 w-[150px] h-[150px] md:w-[200px] md:h-[200px] rounded-full bg-gradient-to-br from-purple-500 to-purple-950 blur-2xl"></div>

          <div className="flex flex-col md:flex-row flex-start ">
            <Image
              src="female-developer-background_665280-9650-transformed-removebg-preview (1).png"
              alt="Avatar"
              width={180}
              height={180}
              className="relative z-10 rounded-full md:w-[250px] md:h-[250px]"
              quality={100}
            />

            <div className=" md:mt-16 md:ml-10 md:text-left">
              <p className="mb-3 text-lg">
                Hello! I Am <span className="text-purple-500">Tooba Riaz</span>
              </p>
              <p className="text-sm">A Full-stack developer who</p>

              <div className="mx-auto">
                <p className="text-2xl md:text-3xl">
                  Transforming Ideas into <br />
                  Scalable{" "}
                  <span className="text-purple-500"> Digital Realities..</span>
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>

      {/* <h1 className="text-4xl font-bold mb-4">
        Judges a book by its <span className="text-purple-500">cover</span>
      </h1> */}
      <p className="text-3xl mx-auto mt-10 ">{`I'm a Software Engineer.|`}</p>
      <p className="mb-5">
        {`Currently I'm working as a ${" "}`}
        <span className="text-purple-500">Freelancer</span>
      </p>
      <p className="max-w-2xl  text-gray-400">
        {`I enjoy creating delightful, human-centered digital experiences. I am
        always looking for new and innovative ways to bring my client's visions
        to life.`}
      </p>
    </section>
